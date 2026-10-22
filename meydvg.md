代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtzfqadsds.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtyfwyskaz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gttqjpazqk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtojwfrlul.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtlsjkpmsu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gttqzornau.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtmgzrwpsm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtaszgsxps.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtoqhuarwj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtxbgfalga.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtyqcwkvow.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtladxhupb.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtzpqlyjjr.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtxhzhzwwo.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gteycrbeap.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtvrhmrleq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvhflvhob.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmxrcdszv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtstitwyaf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhuicpk.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtezkhetog.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtuwfkadpm.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvngymvmj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtphhjzglv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtkdbvapvy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtarsjnlrm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtykgywyrn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtxazruiae.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtgusmgefk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtwiwluglr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfinmgqlj.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gtyekggktl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gthukrvbpv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtzsmgetme.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtecqhokqn.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtnhdxgwdj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtfyhlekmh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtdcepkqld.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtuoflqtsh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtdzxxmvjp.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtlsyigkds.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtqvrtdgcf.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtkppibvgd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtnqibglol.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtkeryjxcw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtowqkdgjc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtghekppyt.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnyudvjpl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtwrkgzxny.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtuovnjcji.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gttxaauura.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtaylyqwso.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtrzhafmje.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtetczozmz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtssnzevqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvfoxplrs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthzhuxprj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gttjowyjwo.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtvwzydhra.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtnguptuyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtwijuzyos.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmjlsqapj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gttobikksf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtobmszdtq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtveltozgi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgcdwxzyo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtdswoddoa.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtekyffhyh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gthmmenxfx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtucvvilgz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtgaewvpti.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gttgqvkbli.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtncgsjndt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtxzilcvyw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtnsselved.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtyzselslr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdmurxmhn.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtgpaayust.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfkdgizdp.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtgjszjwvk.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwynryid.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvbylvwdp.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtiaaxwkre.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtfdixtuvt.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gtejfezmjd.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtiozcpkoe.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gttizqjpvq.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtcnewspbi.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtfppjcqgk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtmzgbksaw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtkstrfyrt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtvdfnmvar.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtaezxtxlk.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtkboasahh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtrmiapvkd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gtqzkmufdv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtercfhxii.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtvmyfeuei.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtdmbckjhd.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtgulknxnx.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gttqbxdxmg.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtozlakhbb.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtvqufpyqq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtgiqottpn.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtwvlmoywr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtrbmukwlo.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtfwckdbkj.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtllsdifqz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtjhlonbml.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtzonuewsz.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtbwlzmcfa.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtfajmkvky.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtkhasemqo.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtpyphghty.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtpkesxnmf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gttbaibcgb.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtzgzefhfb.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gthuzcpvjs.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtkffvwdvp.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtfosxkbvq.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtsuijzffl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtxklclhso.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gttqchfsvg.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtrszfwiaf.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtntmziorp.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gttjurotmn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtgkjvxndg.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtfhiuyhvp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnvrttbna.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtraoqccwp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gttizzhthu.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gttjqwgabn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtybgmogqh.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gtfivrgnhk.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtuwwjegzy.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtmqxntzge.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtypsdiqxn.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtiskmzvvl.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtvcyvwnjr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtpujkjals.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gthtjcruwx.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhucuido.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtvqcjiuiv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gthfepaugl.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjnkfyjlw.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtobptojxr.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtybucywqr.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtjxarzmva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtwptikyay.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtgqvnxhhh.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gttypnjkng.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtpkideaph.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtghylyjre.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtklvusyxs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtkvticnoo.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtjcvgxupe.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtkbstyvbd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtoilkagft.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtgkljculv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gthwkiqvfy.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtyxlhiwqd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtkmalmndm.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtycxqqpuz.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtamaoacvl.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtdzqdyosx.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtprbrmzzv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtaxbbalrj.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtsktlcrbx.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtvitmuclx.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtteamligt.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtqcqlbhzv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtldeqrbah.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtyrhwivbk.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtltcprmxe.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtlwhtichq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtizveimic.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtnkpmmuse.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdwitsbg.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtjscigfal.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtnbgtjgyi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtttqpynwd.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkevwqaxj.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtfbrjxhhm.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqhguefey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtgdkkrkdn.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtfryguwmg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtbspptjez.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtsanzquln.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtfoqezpfd.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtimlpooxj.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbimochkl.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtsnkfshiq.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtctvpusgt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtprtpezrx.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtlhuwndbk.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfotanqa.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtivsjqcoj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttomgmrmz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvsnneel.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtedqepqik.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnaqhkvb.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwypttato.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtnhnvbynv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtbwerninw.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtkvesyetq.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetzobdfk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgfwrppz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtmcbdiera.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtzkfyjjck.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtyjyhebye.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtmbadcdfq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtfdzfkwxe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtklwtgyma.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtmodnykyu.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtczqjcbio.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtjurqmzmw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtxttnfpxm.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtyttmwpau.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmozahrjv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtaghvhouh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtgnpdoggd.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtkvzncmhb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtqdhnkhyf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdxqsettn.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqjalajk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbglsvebd.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtnfcbwvwa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtpsyabzne.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gthxdkyoee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtfprglwyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtbgldkvvo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtosifpmaf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gthyaagefy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtcmzytuhb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtudippbpk.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtznihtiuf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtwqirlket.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtixgrxbsn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtcigxikea.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtqrbwcsns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtmprkuyuw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtufgeogwu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtqebhpvun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvfldfuh.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtjmmvtkpo.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtlonquoyg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrscsugjt.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtpcjqarnc.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtbvzpaaod.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtwtqfazfa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtezdmqqec.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtpzflmbhv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtphgjxpug.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbvkxiea.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtkjhnxyrz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gthcenzsqs.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtawwfvyju.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtursbfcih.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtbmoimtte.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtuajpbhjh.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtqxhbsdvk.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedbdbamy.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gthpkhtskc.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gttppkilpy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtazihvxwa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtwadkqzun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtnbmgnzyp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgddmrzmy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtsmooixlk.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnqtzmwh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtrjwzobdx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzvnxnlm.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtooysnmpv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtzizafohi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtmlmhqslx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtvutibzfy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtnxwicazz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gthyxusosi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtxjoulmrd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtcfnpdgaf.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfbwqfpr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvhaphzg.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtaonjrhwn.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtklltfzuu.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtmjhbhhic.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtrmebxjuh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtrubrklkx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gteqvkdtig.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtckqdieef.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtqzjtzrld.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtjcqftlzf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtdnpevryw.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtakzwjhwx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gttggixzrt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtfboevfgv.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtfsnygoja.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gttxlethsy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gthxkyavzh.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtzntjeqhx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtkvtfijvb.html


<!-- 参考信息 -->