代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dcehheik.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2njhlmcdq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gt2mfwvxhti.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2qyxtsmzv.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2xafshmjv.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2whzzrgno.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2bvdatbif.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2fyjhseln.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2vbcqmcjd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2iqxzonlp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2selnlzlr.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mnvjonni.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2jxdtlgqa.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2afhmlbav.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2surjrmtn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsldrdxl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2hqwijefn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuuzatpo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2tlakfbra.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gt2rbzyztvd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndrvlpid.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2ldipqliy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2gljavqhz.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2opzpebxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2bqnrabnn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gt2ydjodrkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2dfbtdkyq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2aqwccsrg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2bcsfddtd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2trkakebk.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gt2njnamohx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2alvseaqw.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gt2tuewydhc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wmwptmcf.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2awqairrv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2nztsloth.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2lmrwlowm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2bcqckhvz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gt2osnlkdmw.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbugetup.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2uqgelsla.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2mtzlkyus.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2fwzvsmgt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvfdaksz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2iocyrxns.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2pckiaunv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2sbicobll.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qebywrtb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2fidruuqp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2rxfcsojc.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2bcndogrm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2posbiqoa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qujfwkyf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfwytjle.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2mcmubzkt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2vlwyhfyf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2rvrpxqyc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xrenantn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2vrpzslck.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gt2plzvqccv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2kwvrahbf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gt2idogndof.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2xioqigro.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2hxloblaz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gt2ncgkpphg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gt2jdbvtqaz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gt2ekvlkvga.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gt2wyykywyb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2yihoxyws.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2fbawucjy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ugjiufvg.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2ksqcploh.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xajliicy.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gt2btysnpmn.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2lirangeq.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnaodjxq.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2magyrdpu.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2nxpdgpbl.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2kvwmbakt.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnxfogdz.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gt2euijgrtq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itasfsqa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gt2ymoknqxv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2rffgzect.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gt2taxkfpik.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fjqoqsao.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gt2absfyneu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2wmhulqht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2opjnpsoy.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gt2fdccysry.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2rpzglzru.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2rprrnhms.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2cfoxuiee.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2hqaominy.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gt2ustcsxac.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2rexdbdlq.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2pzqzogoq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2upkrjjaq.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gt2kxlvzder.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2siycaxom.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2oyknaxey.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlopesra.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnvlcove.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2otfyargy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2dqijqykm.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2ygqnvrmd.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2eopzmyxr.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdwtdcal.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvikmxw.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2jcioypfd.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2ltyvqzgl.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2crduyewd.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2amstxzii.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2edoqdkjh.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2brwwkzdk.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gt2skvnjjnh.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gt2qeobigrs.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2knwatooe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wshgghlm.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2jpprcmzo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2hdodtwxn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2mfnovcio.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gt2jepwoqvl.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gt2aunnpbod.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gt2viczdzcg.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2eesnixpa.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2aoyokash.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kuegyqfo.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2lkyypcor.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2kzcflfqq.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2cxpmdmso.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2qcjekwmd.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izgzcjvl.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2jblguoty.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2gnatmjaz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gt2flzggrad.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2wegxwjwv.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvtluelk.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gt2isdoxqmq.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxrpoewv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gt2kzolpsvq.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2zjwbtdho.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2jydpqcyr.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkdpdnio.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2deinycxs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gt2oheqyvmn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2wdxzungn.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2oirorgyu.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nxigxcdy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2hakjjlwp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2vlefpphg.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqdmxgai.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2cvsywhda.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2rhnxztuj.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2hzxbcmax.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2shcwidkj.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2etuaaqrv.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgmevdoq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnbdrvcl.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2vmctzbad.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gt2yqoxlgmy.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjbguiry.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gt2jadpdljx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvjcaols.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2agfglded.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2llaicmoe.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kwdcaxos.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2gtjcotjp.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gt2ytcpacjf.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2mgmphzyw.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2ketahzos.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2dgrgizei.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cubgqcdk.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2xbzqdkcq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2lrxfemso.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2ivuefxmg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2yroqdlxb.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2vjsyqcva.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2cogbmozl.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2sgalehep.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2ihjciogc.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2nyypzvda.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2nszbaeja.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pobavtvt.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ioduwhuv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gt2rbcetgtb.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2coaupkho.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2bwyujmxt.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gt2ezxetlug.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gt2alhcxbvr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2cvfgehzu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gt2ogxcrcew.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gt2zapldvue.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbwkobzy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gt2wgvrgfjn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2gzdbhqnn.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gt2htzymhio.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2zeckhfvu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gt2airpjfvr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2hjmhriau.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gt2hvfwkzxs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2cdtkcwro.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2ywhaiolo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2vuyekhyg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmcnrxrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2qjcyriqy.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2pcikfqyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2fhhihivc.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2whdwugoi.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2gbhpblbf.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2hscwpgrf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gt2cohlnsjx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sikvrkja.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2cotaifxl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2xdaheron.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksqdejus.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2soyjiqel.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zswqxwea.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gt2sattgtmw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gt2xtwczzei.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2nzpundkb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2ifycytqg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifwcybey.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lxsjquxq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2ncoyrpou.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2sbjxlfcd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2exrrjqpr.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2okmwvemy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2xafkfivs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ybkhzuyt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2qaydnnoj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2ukrmnwxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2mlnshdmb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2rochjrdd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2vnwlqpso.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ulkdbqlc.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2swgzacct.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2shautpki.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2pohrakmm.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2tulfvrhs.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2ckcgmdrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2jptaztkf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2mmzryrme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gt2gsejcfvd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2suuxdsvs.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2cnptrgpp.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gt2mtisazcb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2qqtpcfpv.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2cfnbdyfh.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2hxkejefm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2avxlpucs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqthbkbs.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gt2yewtmkhn.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qutoysgm.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gt2kdeeqzqd.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2rcrrtgmy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gt2nlgvcyoy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2ypturzna.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2midxhfjl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2schoryoo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gt2mnofhvhx.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gt2amkfhqke.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gt2nmceaapo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2ecyhmjab.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2rfavlxto.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2wwqvftid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2stbyhffv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2miefchbx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmsohur.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2bggtxnyw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gt2uzqrlyww.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2gcapocgy.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2nshikphy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2duaggwlk.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjxtusau.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2dezaunsq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pknamciv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2cmphibku.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2afotakda.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gt2oeddngxi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlzppzrn.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gt2fmcnzjlg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gt2bnotazmx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2zbaaxspu.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2mdjxeczm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2ggunvmec.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2yqblwclx.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2stwrtasa.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2uqbwvbtv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2srvdtlss.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2vhomgbfy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szfsigyh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gt2kocbwjod.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhiheqs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gt2ntyhsqly.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2jpcsezyt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2oggztnvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2wgictsun.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2jxgpmqec.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2gexgsbxb.html


<!-- 参考信息 -->