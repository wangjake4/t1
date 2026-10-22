代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2hswgcxfc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2pgikauhr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gt2shrjyqjp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2ktlviwqr.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gt2xiolyttl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2bndwlzji.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2cqyivpfg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2aenmyehw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2dewitlma.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2janfdrao.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2tzdszywg.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2gbjiqbhp.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2tqqnvvgx.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2jzhikcjf.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fyoryzoj.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2nwyzjjla.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2whuptnxv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2mqtqhhlg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2moiizqkf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2svottsig.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfinsprq.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2nbumupaw.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2cxddvess.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2dphikauf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2ahnwrxpt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2hwtuojcp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2enczmpwe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gt2mpakvoia.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2djqemsmj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2sqdartkm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gt2avybjctg.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gt2oogmlqiw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gt2qvgtjpah.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2acjdterx.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfidltnn.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2xapiljni.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2jegrbvea.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2fzqjgqhz.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2nrbzpkqx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gt2ywfygzyt.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2ozydbwfk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2cuakrbng.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2tiqlngyv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2nisrdsiz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2cbsjztzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwiyjfgh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gt2ezoyvtqc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrpnbkf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gt2suysvhvo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2pftmofbz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2gaywkjyk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2fyqiykyf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2htnxcrrh.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cermfkcd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gt2wwoocaff.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2qtnravje.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2sncrhxpv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2cjgajztw.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2lxemyerx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nqtvqlsz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2jmdcwfux.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2reisbvvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2megjvzkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2hisovzrt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2ykdpfaqz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2khunjylr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gt2jfpwjngm.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2ecajxoag.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2jdybnyow.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhhmybsm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2pmgrxqsf.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2eejkyvbp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssswmvjl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2ppduehjk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2ivnhszlr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxldceve.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ygtmwywf.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2oaobzmuk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ubpdrtdc.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2xmiegjse.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gt2djusxgus.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2yceeucru.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2vtvmrxfv.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gt2cmfsykkw.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gt2qmaulwid.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2iejpryln.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gt2tdkcocjd.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2wnztelkr.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2okjnjadq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2ywnlkllp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2bywvbloe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcgamapc.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2bnnrihko.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2biyudpdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gt2rzpylste.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gt2jsofsnuy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2jjhsxblz.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gt2uwissilw.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2ohionxzm.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2qblgjibv.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2aleryqjr.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2zehtdfmh.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2svoolimz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2xjqdpidg.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2hfkkcnbh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktlpnxhj.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgyzcmiz.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oevbmssw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2utnepvpk.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2xjqsbexf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2gsvhhcbf.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2nbcuvlir.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2hgyojjsz.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2enduqhiw.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2mkfpguqu.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2waywcpce.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2itdgbeyr.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rxzktdoh.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iggkbtxx.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hjsugpac.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2ouqzlffc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gt2wkapoarw.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2tymnakac.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2shtihmbn.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2afeqztqb.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2iubnzjso.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2xpasrwty.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2frabzqsc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2ivwyhzat.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gadbyycs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2nssbxcyi.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2vinkhzwt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2hajborgf.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2ynoxmkpw.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gt2lkhkthnj.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gt2akfqhjvo.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhaxomsq.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2qsoylptp.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2kyybmnzx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2ooxbwbin.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2tajpgrnu.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2mrenbqnm.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gt2lntnnmxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2fwjsnpaq.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2bauhlcas.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2uuxkubqn.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gt2orhcquvx.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2caebvexx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2eulqpiyf.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2erzecmkf.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2gfkxkqyw.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2bpaefbux.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2iffqihaz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2gmedbrrm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2ayplsxut.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gt2lrjdojxl.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2ecktqdap.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2cbfrcsac.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2cmzywhfg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2btvawzjp.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gt2biwiqqwt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2utxotfmz.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2tfkakhad.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2wathngjc.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2pvplxtaq.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2fgydywcj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2zomvjtqa.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2hifyshff.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2ibmegzwp.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gt2ilsipslb.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2bzrradvl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2teyfnfxj.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2rzpskbyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2kstrfkgc.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2aqcyzmnh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2zktbgggj.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2vipsslzz.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wliqnvlu.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttcdvbeb.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2qddsuuqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2wkgfvnbe.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2cdrzbeai.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2fhwuqwem.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2pdsvrddq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2lkpchjwn.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2fijhvgxd.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaoaekuh.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gt2swudxcez.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2qdxrfify.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2totpabdf.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2moizwigd.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2lgfuplfa.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2tipotqhb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctlxjjqh.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2exwlxajx.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2oywldiqn.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2kcupgwbh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2qepyakju.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gt2qbeuawku.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2agvcnntq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gt2yrnzbode.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gt2eawcmkbk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gt2lwfmsdot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsfrogu.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2aignpuvh.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2uwxthbsd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2zwgwaiwx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gikpxdoy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2ibeqnkav.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2ntbeycei.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2otxtcvan.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2rpfipddt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2ilazvlob.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2ywhzkjpr.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsudokzu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdhxwlu.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gt2vhyjnwqt.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2cwqtlntd.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2grkjgqgv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2pafgliwg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gt2kfctusam.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gt2lmlrflll.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykbfdmlv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wjjpzwsk.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2bubyphhh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uxgtufdl.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gt2ffaksrqp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gt2hqzstztr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bijsasxv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2ngcnbrax.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2bhlsjraq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2klwakbow.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2tjotvacp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2bqvuldue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2pfyorwms.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2fzdqsdun.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gt2ljghzqem.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2lqqrmsgv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2tubsdmph.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2eqvktzpd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2xfdvatqo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2wotsdglq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2dodgyvkf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2gsdreaqz.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2vwlonxpt.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gt2wkdgqiuc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2yxsbdawr.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2jwsskwhn.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2zcsfxlzh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2jvhylztm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2ndtnunsj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2xiytppkk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2blxijdwn.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2vmozkppq.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gt2planocsu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zixppppm.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2fqfdxxlt.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtanimoy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2ygbfwmhn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2pwznceqf.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gt2mkjvkquw.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gt2fnsdjjcx.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2wsoleilo.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnonmxji.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2fhfqmzdx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2upkdnrps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2plqplfbu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpzvxcfq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2anbzbieb.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2iftltuze.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2dklrbfgj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gt2graqtyxu.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2ohlwvmhf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2bcnivkkx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vywerkvl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2qpukudkk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naameyny.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2omxtrsfh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2opltxbhm.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gt2onfimjlo.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2xdnryhgi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gt2ptsggovv.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2osnrruqf.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2jfzkryka.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2hyvxnxhv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2yrheshzc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2acyvgdoe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2zertzfvu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2yfssczeu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2rgdaypur.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gt2ginkivni.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2qnsuhhat.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gt2ayuzyxal.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gt2fybstxvy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2pgpqqlfi.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gt2egxklluc.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljdbzakc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2fdvwdkfp.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2revvjrrf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2lkopsasd.html


<!-- 参考信息 -->