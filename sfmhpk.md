代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtbfpdfjqy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtlqemcjdo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtxpenjixl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtkgoqiulx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtwrtovqrb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtipfiuhmj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gttkouvzpp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gtxbihtuuj.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtguiamrde.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gthbjldysg.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtndxgfrqq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsboylngu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtskjngume.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtaowaopgs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtzvyiprox.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmugqvtkv.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcyksobnj.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtqrxksfds.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtyujeqywn.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtevxaxreh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpmsemdw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtduyalcmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtjirzpuso.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrauisvdy.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrmqulwsm.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gttockypuo.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtxjfwoond.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtrfyjluzc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtvxgxsglu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtbjotcivk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtyecywwpf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtijzbihuo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtclujwgpb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtxhwyytiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhczyrwb.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtxyqdzqxp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtpfbkaixq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtefslysjg.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gthbazmxdn.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtiuhybcjv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtloudqhen.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxevqshh.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtbckdkobn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtsiwjuarf.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtmxltulyu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtteiylgtv.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtyfghbidj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtvrwkhvsq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtbkzgdlir.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtaxlbtaor.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gttfpnfxzg.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtelfyjflj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtrtfkmywh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gttpqpwocm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gttnxintkb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqqsgpkl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtlporqcne.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtsqiooknf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtgdsqshbp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtatgnwcmf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjpukloaw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbmbjjavm.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtixdatmua.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtypkbmvgz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtnkaywmyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gturxirhkz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttyfxsjcr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtganpieda.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtagphgmue.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjypjcyic.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtfqkckyud.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gttebeboit.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gthfihnbcl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtxlcldbbt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtcwnrmqix.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtdayuwhap.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtsqywqclw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtuskajjkj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtrujbulrx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtyigvazer.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnylfozrs.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtjqedzqxx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzqdvsqfj.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtribgtpke.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtbbblhoya.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gthyuthhjd.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtpiukobme.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtejxtnsbb.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtsydgjixz.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtsynshxne.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtbzqbevrc.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtsnorgnvb.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gthgbzyylc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtirnwpjdg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtxpdkfanm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtglinepul.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqbqrnww.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtakxhwinx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtjbfvephe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtdlzrxjmx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtesxjfzer.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtgfpyucvx.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtbyhvuwdp.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtksmvkjmt.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtgwetgbnd.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtkdqsfxoz.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtoewsfknz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtrkuwyujp.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtdbzlplzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtjkbliktb.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtpiaxdmdp.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtbehwuvpr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtqclsixtx.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtrzjdouzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjovgsln.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtqywxqklr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiabrvjdq.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtbvqfvypn.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtdascecqk.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtjvgryguv.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtfcaoqeat.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtotyitvzy.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtsvftovey.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtsspggssy.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtdlrumpmo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtgjgkwjsq.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtkzthnarl.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypehrjpb.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiczrtdl.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvlghwhp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtqmpfbnhw.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtsqrwebom.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtbcwcvong.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtemmrncnw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtmwtuuthw.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtouenzntl.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtzwrcxcpe.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtwrjeqgho.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtafkmdihu.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gtxipzrcwx.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtdksusosg.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtmdzuyosf.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbihgscix.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtdrgetqdu.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtxcaaeayu.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtdkjzuezj.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtybhcybgq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtfjsvfncb.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtvcgezpni.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmkcghqw.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtwancbahy.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtarzbgpyo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtizktaczr.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtawavxczj.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtjjqmzfcb.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtyqczlvuk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtbtpzppat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnrmdryvc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtyqwtpjjs.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtxjqokway.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtzyryours.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtyenvnfue.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtpucsduma.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdmrlbki.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtnjkvllti.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtaiipxbvk.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtdzqcztxi.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtetqqevlh.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtbheglhvu.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtfxcdktpm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtefrvsnsb.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtobrognya.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtcxmzbmmz.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtaqtndmmm.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtffbsbmhs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtivvesvol.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtsmmdrfxr.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtqphsnbyi.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtwjugadeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtyqypwjuw.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtfytpqsxk.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtwicndzwg.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtfsdiokog.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtolcbhdpm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtensayldl.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtvwprqhvz.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtrzfbnptf.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtqfbqmdyr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtgmagxjzc.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gteaqercom.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtcuqntrqq.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtmjwbdths.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtkxpfrqrk.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtajhrrjnk.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtkmcfrfvl.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtmazkaxlf.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtfiytukls.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtjnozawui.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gteaphuiwn.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gteuovogfs.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtwmzyciur.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtvhxaurag.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gthpcdouck.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtsgifyuda.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtereykuzk.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtawjnnfdd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gtfkcfdmjq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtobpgjrtm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixrnzqja.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtppahaqvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtgeiiupdo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqyfecwk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtpuwodwue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtkmytxkum.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtegjhacer.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtguayvzoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtppjxyntg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtyqgsnrij.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtcvcdzakd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gthpvvyxqq.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtwvxehzgc.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtbjjknppd.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtnshtuwfe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtrtfaqqvr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwngmexo.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtgykclwps.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gttellreqg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmxyhapnf.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtuakqnpjr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrboapsse.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtggcyizch.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtcselwzaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtmelvvpev.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtsddybqbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtznvomowc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtaktqtmev.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydglgfhy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtmguiapwi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtcufcrjlk.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtttfhjpxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtrrptbptj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtqlzqyjvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtmawxmzqo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtcbbiamel.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtjrmbjfbd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtrwyqdgqz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttftsanxx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtksqcqicj.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtjbipfmzm.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtktgffcst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gthtcvzatl.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gttiangzia.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtdrjozamq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtsnfbqkth.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtfvvpwbsw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllfehpso.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtthjynhxp.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtkqwanxjv.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtodhcjhwt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtnlkwqdoj.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtbbwwoaxw.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtedgsqkkh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtvmownwbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtagkfybub.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtgndgwaxw.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtupqvvydt.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtcudrgalf.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtcxerrxdg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtaaoqfoal.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtlmmckzfr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtogugdxpu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtpfxyndez.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtcoskeiws.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtjeyvhbyp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtwislaarc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtyvgdwcbm.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gttltmalmy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtuzuwraub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtuujjbrig.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtpzqqdpkq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtzozrnykg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gthatkvngu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtffoefixt.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtztkkctvm.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtkycymxnb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtuzndugob.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gturfymygm.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtydadftzq.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtekumvvdk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtudvchjyk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtbmvbcxey.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtkuhpoyza.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtjusgljpr.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtowelrolo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtlzxmofgy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtfcisrila.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtbrtqcbya.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtjqpqfjaq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gtfmtepgvi.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gthvamqslu.html


<!-- 参考信息 -->