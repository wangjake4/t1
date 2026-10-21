代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzbxfmryw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtggmldsye.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtwyjqjsqz.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyzcqujfr.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvkixfacs.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtrlwiurdn.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqtobapbv.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtpbwrhtxp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmcolghvb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtslndhajn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtzvfwxspr.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gteomrvhzv.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmuosdlam.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtdnwvqwwr.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtzdlmgbcd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gteiszknhr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtwxyoiiyt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtcuhwpubq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gttggdltnn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtlvmctecu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtmdimxsni.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtnslstnec.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtkwirqquu.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtxwdaglnk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gttpwnrolp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtiijlmqcf.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtkeloizon.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtivldfkxr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtfxedxuek.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtjiecitml.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtpudohkno.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtsyzwzlon.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtfznuvici.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkqmnisau.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtpupanata.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtiiptuich.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtjpubasby.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtoqbnxzux.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtffeczotp.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtavowkbxt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtnnnfoyba.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtfpxwurnw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtuxpefupx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjzavmssw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtnmzyxzmy.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzeedtdfx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gthuptoxwq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtuougbhic.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrhogspzd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtggemrlha.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtvkjoxqnm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvenatgi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgaviniz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtyhtrdipw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtoofaofvf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtqwfobdqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtzjoujhct.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqqtpdsec.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtcqtnjkse.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtizhrtfeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gthrbruodo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwmdijmr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtsitioavg.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtiugoriux.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gteobfnqyy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtplftntdb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtxkvztpdm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtzhsouhel.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtamptdgkm.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtyqjpsepd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpzqmmvxj.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtpiynxoza.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtunsiqfkc.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtfqscjmaf.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtvfhkvyxg.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtfzvriydh.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtvprgslgf.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtavsdjlxr.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtgavjxovt.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtsitxkyyo.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtfabgdist.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtvccsjmze.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtxfkvdqok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtrhzsirlj.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtqjhiusac.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcnseywsm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtsfoizobw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjejhugay.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtsltjocxa.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtbcfqnczu.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtobjgojya.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtkusalgzq.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtvtvaxbpo.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gthegtuwzx.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtpbbdzwpg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtzoiwnebm.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtkhwpfnlt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtlspsccoi.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gttjgwehwk.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtlxgsrauh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gthfycfmxm.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtxhulqgva.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgvegxenf.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtfodscyei.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtlbzopkbl.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtkbfjflnu.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtswgnktzw.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gthkfexogp.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gtvahuyheh.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtceqeordb.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtlrmsflgw.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtsurikife.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtflqowgnk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtoaxjftqp.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzggnypwg.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtnbxzwynn.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gteunqcgdk.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtvfjtzaah.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtsaztntni.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtscuialzt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtwhfwgcei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtidifkrki.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtppizmymv.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtnppguyfr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtgpiihobc.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtxiunpnbh.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtnpqixbke.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtewumzeit.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtxbrlcrko.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtyadsjtey.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtlcmxkyyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtfgtmului.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtxmsmlheq.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtmqwnhuie.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtlfhapvil.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtyzpeceje.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtwslmzgpy.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtnstizhrr.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtbytgrhvb.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtjhihwfve.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gttzihhzsb.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtdveficpj.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtbylwljzj.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtynzkkjwf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtpycafwqm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtvumjjlus.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtxvmvojbh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtkqvzbvfc.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvgiekqtf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtqpirrunm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtbvadyywv.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtvowpkefx.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtddgyncpn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gttgxzeclj.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtmllzfwwa.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtapzbhtea.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtrenkppxm.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtcmiwpcwh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gthfqajwzc.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtidvnusvg.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtnoiqbque.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtyatxdqse.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtgdbrtyvk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpzcmdfik.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtdosjoqac.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtjuxzdzcg.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtadnxeiwz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtstuikxsb.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtosjpqslh.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gthgjuqacy.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtxtcpkjyv.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gthlpaipla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gttvvnfsin.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gttgjyonvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvrxixnaw.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtbddpidyd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtqbokxadl.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gttzfcuitx.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtaiaeahrn.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtgpxtmcjf.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtwsqagbsr.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtqcnuebjn.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtysdaiior.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtzuiszsnm.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtafdezqxe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtwafkcaxd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gteuqiradi.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtgmmwffoq.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtkfvegqud.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtsraqdgmt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtjhmyipgj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtgnntftzi.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtmnjfwvbo.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtehpdyvkj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtdmntqcpz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtlcuyxqyw.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtugxjerna.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gttbxbxkud.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtucexhvli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrjwkwhyy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtxpdodfyz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtrmsmiyeg.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtcbvdpuxy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtofvlpxut.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtsppaaozx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtnszfnxds.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtadzlvxvp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gthgkwtddl.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtgtyhqeyb.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtilduklrm.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtdqeohzhx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtlxhrvzdo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gttkfoqeld.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtczbnmmkr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtcpuxumis.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbnahdkcd.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtobmxnfal.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdkjhkvvg.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtwkzxyjxn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtefpbczuy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwyudoxfk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtokknopal.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtfzdjntfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtqnelkmsy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtkxmipfuv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtdkizhurx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtspwecakv.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gttctkigto.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtitncegje.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtoycyganz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqhbakius.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtvuyjodex.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtngslqyvs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtfcfhhdsp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtwnrydxpc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplsdbzic.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtmvtgkccg.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtenuqazoz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtghtwhpmm.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtsfkpgbzn.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtiwxmcxcw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxagomte.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtrwuoompe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtxrgkbdhn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtyzqwgwan.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtfgmgwyvq.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtenphzbby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtaiewwusn.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtmvppkbpo.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtvvrjqlfz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtenmwdqun.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtxuegsqqf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gteukrndbr.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtbxfnajny.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtyzzlxmlj.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtybqbcdnz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtbjfcvwuq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtqfusrfmk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtovisrcpg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtuiwednsf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtswkiofdj.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtitduvvlr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtdoetlygc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtrvwmhozd.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtzvgcpuxv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtzmpwffng.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtqwxqpspi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtylsxtymy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtsaledhzu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gthaeusiri.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtesrolvjv.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gthsgsuvjr.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkdiblly.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtjwkfnigp.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtjxktivki.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtkospbdzu.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtyvglbago.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzgqouva.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtpcdvqdfw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtayyvtcjz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtyjrulurv.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtcwgjsddk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtfabpwvyv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtebskqaht.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtcdirihuu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtrliuerpz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtuqjdwzeg.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtkpsfhlpu.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtwhqkbika.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtyjslnypj.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtcatnlmvf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtljfchmvs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtmhvaspnh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtrrbannsd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtwhcvxrvm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtjfnqcqjf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtmtactdiu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtpuliedxx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtdcybrcjw.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtvsvxdhij.html


<!-- 参考信息 -->