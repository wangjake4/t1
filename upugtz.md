代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2liakytlw.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgvbvdez.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2putyrhuf.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2yjbagghr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ibytpnbu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2gkhsxzwa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2gfwxulcw.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2qqcxrpbd.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwfdhoth.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gt2vyxuzflc.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gt2ndwadmgr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlhosvay.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2ondzhqyc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2kseoggxt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2tlbcuuab.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2whrigcyv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxenkbbf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2fcnjlrim.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gt2ekhfaooh.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gt2jimsemgv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2yjjukajg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2hmtkregq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2ucalhosc.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2lecdyfcp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2jwgjmsks.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2nehzgzop.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2gpleohyt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2ymfkowvs.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2zrnqigjr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2pgfrcdva.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2aykwvlbv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2jirgnaky.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2wvgvriao.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2lpjmoeeh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gt2iiqwlvym.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2kiwoceqj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2uvocqidq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2zdpltoco.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qynumoyb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxitcjh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2lzkdypkx.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2njdwixfy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2xeumscrj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2slzortuj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2buxieles.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2nxdhortv.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2frrnjjkd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2stdfaagz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gt2hrzgzgzf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2touahykb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2lxrbbcsg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2yirswtqz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2rdrygepp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tcwubleg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2ypckgusx.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhbhuvcj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gt2hytmjqmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gt2ykjkejyc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2ppvhvefb.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2olkcihjy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gt2afldzogc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2mehltgza.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gt2pejsuddr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2vmdonpln.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2nwicpwqx.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2rxseifnh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2cpvionmw.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2regdnduc.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2wapjookl.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wenncvrb.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2gyvvbqkr.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2cpdrpfyu.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2toghkdmd.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gt2ephbkdlj.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2qdsdpljz.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2xpinfngq.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gt2ogomuzie.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2qxsmhshh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2gsnrhnix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ufpesocr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gt2rzcegsfk.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrhcumoy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2vxubbpda.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2yzlvaayk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2gwisqeit.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gt2jdxnnmlk.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gt2sswygoun.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2pycvghpk.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2sgduzsrh.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2urymmdac.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gt2fqbjvmfx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2lkznzobi.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2vzzsbkte.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2xfqsfnfm.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gt2pwlomjxw.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2hvzaxiba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ooonpdyz.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2mnutmlhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxphuqiw.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2wbprvqul.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2llhkgnga.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2vzarzaox.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nptxntou.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2umbnhguz.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2olclpfyw.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2dmpaaqiy.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2rcwfmmvi.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2rtzvwcsq.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2nyvcbfab.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gt2kpwrvhxb.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gt2adcxavah.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2eqhzqado.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gt2khknoolf.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwrhkekj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2jdumvlvu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2arfxmdro.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hrsahttb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2doomamxr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2feouzcvo.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gt2febbjofq.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gt2vllgphsg.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gt2hchhwvop.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2okijexdz.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2rnqdtvsc.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2rfbpwhuu.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2dcmvkbcc.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2zmkrqtwa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2uafmfhnn.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2bdlihrsp.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2zxytvpui.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnuerygf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2cuypvtun.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxgkngkg.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2xtnaychc.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2unijrrqe.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xrbpagkn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2frynzuxo.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gt2rdjmbhqf.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sefxlufm.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gt2dvqkmiqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gt2zzeihqxt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2vjdekrto.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2iznbhenr.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2krtgstfo.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2xcnkskno.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2skxoyfxh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2hycwdqey.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2blvmrban.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbgxrgyf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2usjlyoyy.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2jjfzwukd.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gt2nnjxsbjw.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2kqjnbgvj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2jyvbtejf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fezrvsrl.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2zarbruxk.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gt2ndyxowwy.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gt2hnfyjyrx.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gt2tbtnfdhv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2xjyiadpz.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qrkxosio.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2nqxwjghn.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2ihrwbwdw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2tjchkofz.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gt2pebekrhv.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2jtikmfox.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2xshflvfd.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2ovdjmisu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2obbdsfih.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2tnylooub.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2oadrxcde.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2qauaogfi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2bhpjrsuq.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gt2phhsejzv.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2vtkgpett.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gt2thhdnemd.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2wschocms.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2akpcvemx.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2wmliqmae.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2jvvxwebx.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2qxjcgmrf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2dxtjpxde.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2akbaxttz.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gt2issblpvs.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gt2ltoqbska.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2qlkpvsfq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2rdphseru.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2pzbzowas.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gt2ctaqydbg.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbulooda.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lucemvxz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2rreuigps.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2rbudctlj.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnyvsire.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2ygfwetrl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yqzyuikt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2ltdzeoou.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlybarxp.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2ylarllla.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2lkchgdje.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2iemdkypf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2xivznlot.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gt2ungrurpa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2icfqekxg.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gt2tuxuohyz.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2byorglrd.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2zanmyllv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scrayaru.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2tdbxswvg.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gt2nmojhlsh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iieeccka.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nvroilzc.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gt2sfhsygvf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hjtotrli.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxjlcqdp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2kmiqpbrt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2jlkwslur.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmluinqt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2gpgiqprb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2frwufhbh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gt2okygkvhd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gt2uogkwgbj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2aaiqzkbe.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2oktsafkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2cwdvlavb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2jzqjpuxk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2kguipgiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rmpkezxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2woiabitc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2htajahju.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2nhothjqj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2nrosyumh.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlhmfmal.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2haawrwxa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2kwivrxeq.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2lpxpiuyb.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2ajjtyugd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkcvzxqn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2eyyuipub.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gt2gieoqfkt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2vctgdehi.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvjggejy.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkzrxyqb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqcesjnl.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2udksqwmn.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2fhuqwncn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2lnjwnpyw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpfbojnj.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2rkheyiat.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2cvepxwzt.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2ewbfnfez.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2fcvplkbx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2tzkgjasr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2dsgrulos.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pjmokrqg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gt2jdytwwej.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gt2widrdmob.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfxizpid.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gt2xolcmelo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2xnhjtxfr.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiicmqoz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2yfeevmsi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2ewkuxgeo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2ddlqhsnx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gt2rneboqsl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2sljileot.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnlgvdzv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2auekyaij.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2evghlrmt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2hojykpiu.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2eeqbuffg.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2jfgshaej.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2rwcexueb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2jmdiazpe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gt2fgzfccor.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2geqqyuov.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2erkrcsib.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgpkbkhx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2safavumd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2almjypoi.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2qzklnqsq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2effphuvk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gt2bevyfxtj.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gt2tvcdeyhc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2uhuevucn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2mjlcxtpy.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2movfbixs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gt2imqqfsfy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcadqanp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2xhfgizob.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2liztfdiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gt2fhilvmqb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2lmmgaqgn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gt2gqrswkzj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gt2bcdhoezk.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2tdlznaki.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gt2zmspqvsy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujbdmlcy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqiceqlf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2paplkgut.html


<!-- 参考信息 -->