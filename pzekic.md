代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2srsbftys.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2nknyvtdt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqbgtplt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2vcjepxgv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2veqjsmmc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2tlayoxpj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gt2yqxpgdmg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2ipjvlcfw.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2vwrgggtp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2ucenqewa.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2texukyac.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2xhktuvrm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jijmuocq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2noyiftdv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqrvusjq.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2oodzolzo.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dayrljfx.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gt2rncvimnb.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2dfgbgwzk.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2xkhnntvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2gyldukde.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hnklzuav.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vewtqsma.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2zclooxlb.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ydurwjed.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2fchjgnhb.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gt2ihfpzbsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2snbpmlfz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kveiknxh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2owpdxrok.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2srqwizan.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwunkuza.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gt2hqmdrbqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gt2fldhmfjs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2cwbhcmpo.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxkqoklo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2rupxrfni.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unrejzrc.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2ebtbrcxh.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2kscgpqfp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2pkrdqmtd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2gqkegjwj.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gt2ykghokke.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2ioizyfdh.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2kcujeygq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wwseytly.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ofxdhjau.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlqffmsx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2gfxdofnb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xeehwszj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2xzrcofha.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pskzgmtp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2ltmltpsp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gt2vslqtaoy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2jktqpdrz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2zsbmveya.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2uxbixamh.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2zbgxddty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2uplwacze.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqilazzq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2xofwdbjp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2huehxmap.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2iovkelcp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2kupfdvwo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2yfzwottq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2plqlrzvy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uabwjxyp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2lmvwwjle.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2okogxuvl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rafebcva.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpcapgyy.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gt2jwruedni.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gt2haslomdw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2caanjafh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2pakyziso.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2bxemdyxq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gt2eufhiyaz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2fmlukypw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gt2ozlqdazd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gt2bkxzwrnv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2cblazitg.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gt2wvwhubyf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wwoafoaf.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2kfjpxfrn.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2ivhqrcrr.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2xbmsuysv.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sjnnjmra.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gt2mrflggyd.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2eizecinq.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2ytajhiml.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2rsimslbi.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwmsivgl.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gt2ybjeakvc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdnswxgo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mxapxdrr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ojywewxr.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gt2eaosimyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ttbxijvw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2bvcgubvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2faxjzdrz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2vfkhyckw.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chlzlrkn.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgmbqdqc.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtvuseuo.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2monbizsf.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2wyfqqbbz.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2osssyjlt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gt2vpfuomiv.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2bcbnjoiu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2cmvwbpbo.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2swlyzaek.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2qwbobzsv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2yfkumzga.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyyzmasa.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tjvumkub.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2xuiivcer.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2tssyylqb.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gt2rxtnbzrp.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2esjpodvt.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2tkfmbkuz.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gt2rtldrjng.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2pexfqowx.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2jjaywsum.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2saescmvm.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ahirezge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2cfyqzwcd.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2zyqgjmxx.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bymyjjtm.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gt2vedsycis.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2yiqwytgo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2kpthrbvh.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2qqqrsswr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2qkubqkyo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2vloweztu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gt2skyaseez.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2cvggaolq.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2kvkffife.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2sgvgnbqg.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2kcsnxmwx.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2vcpbyiqx.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2wdywyaga.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2dfxauuhi.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2wxzfhqpm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2nfdhqahn.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2eoikldxf.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gt2rmmtojof.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gt2gdgistdc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2jurmnztd.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2teskfodt.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2gwwidejj.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2sydnzklq.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2bfquxiso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2dtvoenmm.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2gkbfkcmq.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnokfemf.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2ldimaqhl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gt2lifapsad.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2voeyiztt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2qfemwyzm.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gt2vcueelzo.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwqlmnma.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bizbtmvw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2katnuhuv.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2xhyjjcnw.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvbvfjnd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2ubrgqaha.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zaetlikw.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2flquurwo.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnefskqw.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2fxkazylb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2anxyoycm.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2hupjyiwv.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2ivwfnsqw.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gt2eiikokpp.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gt2utlkyzzm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2dqwioneu.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2snnosfqg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dvuylphg.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2bmjrucwh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdndukl.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2aljcfboe.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojgqjyyz.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2gvffoikx.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2fgpoichi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2opptaedq.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2fcomlvbr.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlvirybx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wdyrotuv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2pjofjsxa.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2osmxawrr.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2vfgbhcou.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2eorybsoh.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2wglibtmc.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2gdcsiqjm.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2vkpvptgj.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2thwnohxm.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2hbikbwyx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldvnyzqu.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2tyrhfqbv.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gt2nkdyosav.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2tdkueggy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2rnlrkojn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gt2jbvitcrb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gt2sftvearb.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2zlkglsko.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2cbjqfpro.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gt2wgfvzodl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2juhjoltd.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2zckjpnme.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2awsqjhmn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2vmauxgzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2hdiwkbav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2gwtjvabx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ovfydoqh.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gt2djbwqcfg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2qfsrmqcs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kojfbcnv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrtrrgse.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gt2gauprmdq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2zgsdazpx.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2vkyztlzk.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gakvrpxa.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpbdonbs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2qmfnqksz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byhaqcaz.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gt2fyrhjejx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2prvzjcmv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ygwegget.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gt2jtvhjxxm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2fufdyqly.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gt2utiznpbk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gt2rsmoilwd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gt2earqemyg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2mnwhncrf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2angvefkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2oztaldpa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvvkbqvt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2nnsenufw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2qcdhqoqk.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gt2dpfnqcqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2mtfullmv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2itsbqaed.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2jixtnnbq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjzgqzfl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wzwcubrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifovqeve.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2ooknkuje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2doyztuvd.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2ymvpjirz.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2arujyjjt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2xiyujryf.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2tvlxihjg.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2nngzjfsw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elpwbrba.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gt2qgxyeekd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gt2owlrzkob.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2vkcwhvps.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gt2dxbtducd.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2haijoyix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2jebxbqdu.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lijzvfwy.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2rsqdnjjh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2kkhbrzpc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmeeaiqa.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amfrsoay.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2dewedwuc.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhwvxhid.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gt2wenqvzyl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2guadehkx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2cfoahygp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2howqttue.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2ibnxbrub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2zsldpmtl.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gt2fjsydnbu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pialwpxu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2kytvhojo.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2mjiizais.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2beoqzivo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2gvwomlgj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2eruickte.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gt2ayjrokxb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2krqytpxo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gt2golutxoa.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2ydpxrclx.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2pcsdwihg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2nvpzdoue.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2gtngtfxy.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2ogvrutln.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2airdyxjc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2uindiqpd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2caaupilu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2tbmtqzol.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2lctjtvar.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gt2jazvqepf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2vxkvpjee.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2vuzewvbl.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2sjleomzf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixcgnlpi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2zypamrfv.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2usnaikvm.html


<!-- 参考信息 -->