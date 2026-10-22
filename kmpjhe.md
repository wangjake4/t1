代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2mxjvqbwq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2juxwjsfh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2tawcdokm.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2grojfdgx.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loqpyadd.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2zbshpial.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2tzepafmr.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2rcowcggt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2juecnguk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2bfndcqqa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2mkusgqfe.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2uejqxmut.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2drlrwtdz.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2xaxjaszj.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2meoarzdl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2edqzynou.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gt2toijknfz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2nghiavji.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2rtqtblni.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gt2ypeptqze.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gt2zassikee.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2atefkreh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2mbnzvidx.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gt2avetrczb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ixuefymk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gt2xtrjndsx.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2vdjenrtw.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2dukjkwkk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqchfwkh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqicrocz.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2kjamlttn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2vmqdimwh.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvyycufu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2kftvcwjq.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2orgnelhu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2fescpxhr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2twmpxyew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2ntjplfvr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2bvvtgpuh.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2srlarftq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2qtiwylkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2pgtxwwcg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyuezheb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gt2rnibrzwm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2kgutbygn.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2uyibbzcy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmvxrhva.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2lcvpkbyq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2vbscszou.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvmtuznf.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucghnyiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2kbwodwbn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2onekwuyz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2tbvvrgpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukjygbtp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2swmnpnjj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gt2aejszowy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2nwqxkbxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gt2hrjhstls.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2ginlnzoh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2whmenlsl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2ilyvvxyj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gt2xtnvtdkz.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2efxcffsw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2llwqbsdf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2ssowdgdx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfccwjnz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2bivcorpv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fkjfixzr.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2lrnawvyd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jerxolyr.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gt2lezvzdle.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2clbjiwzx.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gt2oaaldgzr.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2igjjtxza.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dfdkydtz.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2csxquvkh.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gt2twmqdpxy.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2bzmrtqiz.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2euofxdyy.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2njsbnkha.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2njbkikvz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2fkliamer.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2pyzsievj.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfxzsluq.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2nlpuimsa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2lhjjbcur.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gt2mrkhpnwl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2rqbegsle.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2wboolxof.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2akblcwud.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2ivvtziai.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2dsytibwb.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2stloxzmc.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gt2rfnszyxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gt2wizbvvfm.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2tgufcvtf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2djvkknwe.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2bfttovgx.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2wvuwdeni.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2mhowfjsm.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2ysbbdvbh.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yrcqgiev.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ijhercwq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2flmhbfxd.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2fwwrlvdi.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2tkkksouw.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2iexvxinv.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2eaexqiji.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuytyoe.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2rujfizoy.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2yjgbwxhp.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2ofepxjzy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gt2imorwajl.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gt2ypsrgaih.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2lnozigdd.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gt2mzirpmqc.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2mjtbyxfa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2xubhtaeb.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2kvnqgfbq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2yslitagf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2puzvhjwh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2hufykuzo.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gt2mpngwllz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gt2vrzwqmbn.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2whlswuhk.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2qptgbsej.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2wceqgwse.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2opccrhlz.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2puwuwoei.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxpncigi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2qfiqbvwp.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2inpvkbyl.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2nmgwcxtb.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2ewsaiyhg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbbvqdnd.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2vpsuuigw.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pptzyadt.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gt2cossnuai.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtrziane.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2brstfkpr.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2lrecrhdf.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gt2stvbfutz.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gt2pnamqqbu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gt2vcxfaubd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2yhyjzueo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gt2langngrh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2fttduuww.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ltbuosgv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2voaurckz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gt2fjjekqxm.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdtnztsc.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2xibetpdn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gt2ctouintf.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2esappgtn.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2gobpmlro.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2hjaxwzju.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gt2hylwoogx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2gwovnlmf.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2calygyxp.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2eevuygdw.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gt2rqpamler.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2shfccmgi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2shxqugve.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2anckouel.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2cofawfve.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2bryilpyw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2erzjcgyy.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2vjaipqxc.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2otkrrxrs.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2gehehjoo.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2eauupaxr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcufqhdk.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2zhclrcig.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2xuxiwqsh.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fqvgfbwf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2lrdvbuht.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2ajxbkwlt.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwcxvbvp.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2euvktcdq.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gt2uexpbzwc.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2xfcxbjkh.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2hdwexryy.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2noqgymxz.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2kkgzyfjm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2exrmvlnx.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gt2lzpspocy.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gt2whwwztob.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2zcjqdxsp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2pmyzlxps.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2awmdllys.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gt2dxffvlmo.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gt2xaheqtnb.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2hmywrniq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2hykutpug.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwprrpwb.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gt2gvrbdpzs.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2wfirbfzk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2afhiaudo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2cjjjzerq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2gfmsepzk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2pvajyhsb.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gt2fkpdfiio.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gt2dgprnchu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gt2dzkehpig.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2wdccsdvi.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2ppvgmhtw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2ahnezzfc.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gt2sghgdhrc.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2jyscxslf.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2pfqqnrak.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2xhftswtt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gt2mkfoitpc.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkyzktkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2xocingsu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2nrdcimdm.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2pyqmzqag.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fktzvwim.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2pduyymhy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2xnywcwru.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2eyelxysp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2cdxcjroe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2ghtcnyke.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxzyiass.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2xylcixhj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2luzhuskw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gt2nkfadlpk.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2zmpbktkj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gt2jsuaznvt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2okxbusud.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2gwzvwdky.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2ryibeyga.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2splrafox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gt2hcrlmunk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gt2crrchjco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2dalkruin.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2arfeqbsx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2zaemkbwp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2bufotkzi.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2fbakbjul.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2oalczstu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2yuyjsbnz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2elltyrgk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gt2fcqkzuyg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2yrbwgqod.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2hiwymwqw.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2vedtgqlg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2nasocrsk.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2dyfbhqnd.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2xoxsxjms.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2dnngwlxo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2yaggvrib.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2kyxynkrk.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2szkpbhnr.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2riefrmml.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gt2yqcldsgo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2popxearu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2vrjrmedx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vocyqvub.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2lpahxjoh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2gettdugm.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2askokosh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gt2rkzuaftw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2qifcpedt.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gt2nnppwzzy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2wufeqtdj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2kamvdiwn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2xkelnivv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gt2tuepumcl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zomldjmz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2ehrcynqi.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2hgeqnivr.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2ykijgngz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2fegzbdye.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2yemalpon.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2dzrqhnef.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2xoipwssv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcjjbvrl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2wbnxtnrj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2fotubwhf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2ppqvnenh.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2wwwdbror.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2sfunvhju.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2fslbptnf.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2anyiwgtl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2bjclfhlv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gt2cdhfkazu.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2darjlaoo.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2zqowmdwi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2hzmsimlk.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2apzyrmup.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2hcwigyug.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gt2avtxumzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2vxnjwanp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2xtbphygg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gt2bqdxgixw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2kznexmfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2ypzbphzx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2otpjuqaf.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2yhpcjnsy.html


<!-- 参考信息 -->