代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gt2jaxkqcto.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2xqmifloz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqdvbnu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyspvnec.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2tqihiwcq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnklnnif.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2uhankzvz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2rwqwdvin.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2heekickr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2igzmyynx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2oeebezmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgyzvscw.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2pdmdaoyz.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gt2dpyafxnw.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aotlnlsp.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmcjvfqw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2cwgqjsox.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2pksnkjpl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2vcxczipn.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gpbjgtkn.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2jtbjrmbl.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2hnkdrmar.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2gxisikbq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2bbshrcpp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2nilcavxy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2hnzaawza.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2tztwizsv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gt2ktffvfmn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gt2rqhvagwk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2aberbolr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2tqhsujxh.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2hszusgbl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gt2hjrefobo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gt2cqqnzfoe.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2ycoveila.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2dnpfxajw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qafwoxxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2kmcophcs.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2ghnvdjza.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2guykezye.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gt2tuiuuqei.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2lsgbqbqe.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmslafpj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2rssurcdz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2xtwpdjdj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2golxzwfp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqiiqvnv.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2sjsmrgfu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2izhwhqpq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gt2ifxxmhjp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2sqnvetfl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggqgriea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pdalfkmi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeffllm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gt2sujmtcli.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2utrkscxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2hdvtzahw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2lvvkfwei.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bqrjsvjo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2plhgkjph.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gt2choecyny.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfptyvzw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2yqoezyvn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gt2omfwrvgn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmhjqgfz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zibyxhep.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gt2wwfxxubo.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2bvjmjjen.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2xotlhfef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gt2brdgpwcs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2qxcbaytw.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gt2hzuljptu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2fbfvlhnq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2ibgywmzn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2apwoiliv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2jcdjxghw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhwxnsrc.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2yggoipkg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2guhwmchv.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gt2juabzygo.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gt2ummhuqhp.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2zyrhjwpw.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfntclcx.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gt2oiibyefp.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuwqcczd.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gt2tjsowlqr.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gt2azleeshs.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2swllnams.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cobbncth.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2xqouehoo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2yfwgmstp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2nnmmcbpd.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2ljccbukn.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2ockpjmme.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2ppnqxjjy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2opdbyhjf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2rzvutivj.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2umyiiqga.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2rxuglbda.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2dulrchkf.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ulphoqce.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovfkznbr.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gt2tjsmdlhc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gt2dfjxayms.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2gojktdyi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2umnkchyc.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2xlnhgrxe.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2rqehgnvj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2bkjwejlp.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2syyalstg.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kutwfpph.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2irszjcbg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2fcqiuuqo.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2ajlabaqq.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2hftzskqr.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvvlldze.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2pthqtyoz.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2vqlfwrws.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2hfgatqrt.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2ylkyvech.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2gelukfrd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2eevwshgr.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2hjlpjilo.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2hixnxnzx.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2gkbjkklk.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2jzdoamsr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2laoosaxx.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2qekhdxmz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2vtwbrgyn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2dhljspll.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2fsqbxvez.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2wobbawch.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jggtrhnp.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2yaqqqkqp.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqbkceen.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2gqnrfwyr.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2fcqchfee.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2rvgfkkow.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2ctwpcjdd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2tuxuwwrn.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gt2towlxpfq.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gt2jjfpxvsn.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2upleikhw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2dfwhmnea.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2olflyygb.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2yqelqawj.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2itjybsaa.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcquaona.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2hkzvalao.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gt2zfvoxibo.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2nulshxfu.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2agdcixue.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2qcmaysuh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2hbpnioqs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2phvooess.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2rvoczyih.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2sbxcjsxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2sqydqyku.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2qvqscznm.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gt2iwdutflg.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2vqysjpuv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzznhucd.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2zpfkbdfy.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2nszomqqj.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2zyjfumog.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gt2xqcrchhk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2tywmfdxy.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2smeuudnu.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gt2pzyquytr.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2sfkhmdhf.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2rksdjkon.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2lmhlvifx.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2bskptizt.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nnsyiglt.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2qphtcvah.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2klwfugmj.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2gmyjdnvr.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2ckpctagr.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2kyacstkj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2jzqehftb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpgjcimz.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2ylalrqlc.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2rpovidwq.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2pcylghwt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2wjhfjxkm.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2hspdowzq.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xggstfur.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2mgpxjhew.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2xjusbrhb.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2asyuycxs.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2qdavhddz.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2fiebjhih.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gt2nipenzre.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzeservi.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2xupmvtel.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gt2ckeqkuzp.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gt2nasrymcv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gt2cfxseoek.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2lbndcwlh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gt2djzhgllu.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gt2nhthgerf.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aztrxupt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2ppfpshtp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gt2fyyxakif.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gt2tupinvir.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2htxpyhul.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2ilaomnnc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2qddkeqpy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2pgkxpogf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2kgtsfdmo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2dlagzbkw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gt2tthbajqd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2twtytggn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2xdxcxago.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2euosldil.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scnfnwmm.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2pcftwtue.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2eaiqgugo.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2efpvfmtg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2dvkdumks.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yozgxjri.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2tqhnkcsb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2qlvuagmj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2kxoblfpw.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gt2yrcqkikn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2klcilaam.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gt2kzpvkacy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2jkmgehtt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2hrkbfhms.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2whbexzaj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2vqnlpagp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gt2myeabmwi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2amjvhikd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gt2zelcrkiy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2snkfrxkw.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2dasflpam.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2smwlpmsm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2xorqngll.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2dtuiimlh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2thanhurv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2sucfoppw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2scozszwf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2kioadscc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2shojllnf.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2mjfuonbl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gt2embqxiqi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2hhqiwozq.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2czstzqwd.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2kugoyrrn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2plcfzgyf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcszxwjo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2zlpypcmx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2oqtjjvse.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gt2adcikkyl.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmlqjlnc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2deujkjxv.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2ncrpdmim.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2lkjzcnda.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2vjcjthxc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2irvrwjqt.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gt2ruqzdqos.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xolrkokl.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2bzksbuua.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gt2uezuqhqf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2lifbbmpm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caskjqmx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2sqnegxri.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gt2rfgwrbij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2upnjsjlk.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2qvrtdmef.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gt2upubqoqd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gt2tspelrjk.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2nxfkzkyc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2lenfmjav.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2ruvpsnug.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bznovqox.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxfsctor.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2xhvlnztu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2ezxbarep.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2feltpnfb.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gt2vieawgly.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2pewtbicw.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2khnpplkm.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2mlcsondg.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2hlqqoxrt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2romyizby.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jmalyoil.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gt2wtcpzbzb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2ortigmtp.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2uestsdan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gt2xcojatap.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2iuetnelq.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2equhzabf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2pyllvghe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2umfsnlfq.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gt2zwizssss.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2tlhpzgoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbbsgbpt.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gt2aajinsdb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2scuhjcva.html


<!-- 参考信息 -->