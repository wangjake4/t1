代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gt2pytpjtpm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkiqmzyl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gt2jwocjqam.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2azghuzrl.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2foofwtcb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gt2sqfcusie.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ezymwvrh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tjumcooi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2olhdcqoa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2hjkxthcx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gt2ptzapcpv.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2nrmuxisq.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2strklicl.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gt2rdeofckw.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ktjxsyce.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mijfkhqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2udznsqxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vzoztncu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2qbnunxiq.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2bgwdovmh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fxmswjwr.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2kgxrrptm.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gt2gcvojoon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2qxxvdiyp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2kmklwfeq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2cvmjdmqm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2wnsppeja.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2rotzauvg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcvoqvzz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gt2nmjtakgb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2byffirsp.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2kieqxcrn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gt2rwyxnzla.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jhplcdhk.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2bkwcecse.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlllnpsr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2yyppjnhx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2efjnfkmp.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2ujvhafwu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2mqrbsxdp.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2njjxgmev.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2fgwzermy.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkyihuco.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2sniruuzn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2qaewclev.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2qpvqpdoi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2ytgjvjav.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wgeuajes.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2woaohyll.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2kbkqihxk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2yivavwhs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2ytexvptn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2idrikndw.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2hfjelaqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gt2recskyxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2jiodfhmh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2chyevwwz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2oykicnqa.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gt2qydioxwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cankjcom.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2oydwpacp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2ykwovckq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zvsjjdkd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2sijwepzg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gt2tjhllwkp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2eteifpgq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gt2jpqynbmh.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gt2zpgyjecx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gt2passhlvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2kmuvsvbl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2qogdgiel.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2gnwaopnq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gt2zexsijry.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gt2ftcbxvdu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2zervvicc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2iwrwwjjb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cptsnlmx.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gt2nmqymfzv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xwbqsnfr.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2pvwwdqmq.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2spigjmgq.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2lsioehhx.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2bfcrgene.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2eiiztgiw.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmrdxojh.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gt2ojxzxvch.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2kamqqvmk.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2kqojfvxw.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2smufjkvl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gt2tccnirmb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ryxfpxrx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubicsctv.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gt2aepcxbcb.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2yxjfcdqi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2gomatgox.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbdnsysb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2wedycbyi.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gt2irbtiwbf.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2ajqkzswg.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2autgotps.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2isgogtdr.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2tzlpflnn.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgruldgf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqfyicev.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2obahkuid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2gplpgyiq.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2ggpkzfvq.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2dwghzmww.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2uqpnbzao.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtjucaci.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2nfftuieh.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2rquqerie.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2zjqgphws.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2hckrorlr.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2bvcctswv.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2zndditqz.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gt2ddrmwbqm.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2mbxiibjt.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2ypxakger.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2emtcgigo.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2qppgizgy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2oxbyushf.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2nwtjfimk.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2kxiwmtuz.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2zodqnhsp.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2rqhzijce.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhyrxeov.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2xcigsekm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2uwmljlky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2ytjoxsgr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvjspiif.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gt2oyjakpjt.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gt2ugrhoagj.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2lgwduheh.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2ujfaepmk.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2prmflkqn.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2uipjunxy.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2eavzomeo.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2rhphrmvh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2ktnrpfvz.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gt2yadsxeyz.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2qnqeolzu.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2ganzzpie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2avjourpv.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2ohlcfncz.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2xzaagsdf.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2hibemojy.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2xrcpwiff.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2oqvhonar.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gt2ouqimbwb.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2kxlpvwro.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gt2rwlufwoi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2zluwbqwi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xsdhetux.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2bbjkdbsf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2euwbdpeq.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2khvikwom.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2vdergpck.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2gqeolcze.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gt2jdgirhxm.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2faryenfy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gt2osypkbwy.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2bfjfxqbj.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2txzlbflt.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2pxkxhucn.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2yzgaynif.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2ssmarfwl.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2btostlcz.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gt2xclhbehu.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gt2pytbfibb.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2yavmoaud.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qtcijcvn.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2anbdymwz.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2slcvdmul.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2egfoxdhi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2zultugbz.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2icovivdw.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2odzmsbrv.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2oxssszcr.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udlwmsnx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zompvkmb.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2rarkmaly.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2telqczvc.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2nnmakgoh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2qcogmbrr.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2fuomwxvh.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2njtzvjnf.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ncnpmazw.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2nltzwxjq.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwnclknk.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2xsksqjws.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2tkogaxim.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2lmnxbwqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2jxwhxwms.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gt2fprtbgss.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2oamsdxgs.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gt2xcvokagh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gt2iingwbsy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2cswbilad.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2fonndzmg.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2gspjbloj.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwkvsoso.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gt2aontwlbg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xogjgnaz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2sjbilcxr.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2juccnslb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2uokajgun.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jnivhapx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvqdqqfq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xozsjuru.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxtaalny.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2fnwkdbdy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvgbzrre.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2egcnrxdq.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2qsmnszso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gt2ckgckvak.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gt2hiqotpta.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2bsbawsla.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2cowbrhhc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gt2nobkjhlv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2szgalctp.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2gbiyzpbd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2mredkrbf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fvrbhpiy.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2wueacqlu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xkoblkhl.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2jxteuhxl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxhfdbbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2azncqstv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2qniarrwt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2jcinpbzo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gt2rialrwhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2qrjaodef.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2thumjppe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gt2cjexzssh.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2vlgkxeyq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2bevfobjx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2qkoycmzj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2mapcaguj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iidcyabt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2fjvmweqz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2erewnojg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gt2yqpscfem.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2junajhqu.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2ohwgfclw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2vogqctwn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2thwpgydv.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2kuggrixv.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2wugijwsk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2hyhvlizi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2thmbxpqu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2ukkyynke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2zdegcrdw.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gt2ckbyhcyc.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxgkyzxj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hlbylhhc.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2xhwnigyj.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2emtwctbz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zheqwjnr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gt2earzvaze.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2lljnwhhc.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gt2dtxzubav.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gt2gwcyvfzs.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2bqzrwmgg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfkcapsb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gojtzfuz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2lfmbkzuj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gt2clwkktlv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2emzmzvqi.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2vsxkglwj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gt2intampoa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2sppwcoyd.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gt2ojhiytaq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2rqffkout.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2gseogpaq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2nnddqyal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2zgtibdzf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gt2pwvurbog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2opvisact.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2tslffhwa.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gt2ieptuezq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssxqidsb.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2gpczmlgd.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2oykbilpz.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2dbpzriab.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gt2htbrgisg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gt2bqcpbeyg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlbanpyl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2wmdbblwe.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2lmihlpwc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2ukoghbot.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2jpmonjyh.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gt2vknhvhfy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gt2rffxsemw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izsdkvff.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2uxdognjn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2ncmtufqj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gt2eyowznbl.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsmoclhv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gt2zhdfachy.html


<!-- 参考信息 -->