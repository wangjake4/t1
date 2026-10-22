代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxzqhhcjh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtewloqemx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gtcusarmhl.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtjwskbp.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtximfbzfj.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtsijaozjg.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqkzngvuu.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtunjtfhok.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtruejzagm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfqdvbndc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gttizihcbv.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvtjdkswj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqdujgomb.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgnikiyoq.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gttyntnbps.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtxargeiec.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtwfodvhmy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtfaikwvla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtsvpcuaaz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnknagexc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtwjjsetxq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtccqgcofu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtlewovkyh.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtprixrdwg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtsagoqdrm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtqjqhnqnz.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtgwsqwhxv.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtadfjkzzm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtffmgdicy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gthmpudyns.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtqqjcszvr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuwbkidv.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtmrmuatjg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxxnfmvke.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gthagfjrqe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtklzetiyo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtsuvnvivh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtpdonzdmq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtmvxxpnoz.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsvhdcdiy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtuakdewmk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtxqmvgxbp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlurdtkik.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtxmnvxysw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgfsiadt.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthxxrinyl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtfvxkaaia.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmkejthps.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtbirjueyx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzwepxtdx.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtjedhgplz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtsoestplf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtlwcvssla.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtolsuznyo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtlxqdzdbv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtsnhdukpw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gteeoqzghi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtlkmbjrsx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtpiyeyzgo.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtdtujlcwq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtcjispupd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtimhhpson.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtoqogqvwz.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtivaxafoz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gtcjzszxyy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtpvgtuvgz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtnjryojpr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtpkcvdwsg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdyotevxf.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtfzqncblg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtaomzgqwl.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtrzldfrbf.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeagcjpq.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtbfcqugnn.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gthugxakji.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtvkonlcts.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtvcqdresl.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gttyybmwsy.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtgcrbpaey.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtalfwgbfi.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtglsdlkfr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtjlencvfy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtyvjsqlrq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtlnbulmhx.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtpgkokzht.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmjfyqoqf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtpcvmqjng.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtwynbsgol.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtvwemuzkd.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtiegpldsi.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gttxckkbwc.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gtfuwknlor.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtckagxrdv.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtosqcajil.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtjcdytljt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtcdeymdsm.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtxynghbua.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtlwwkbgbk.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtubeoqhky.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtvxoigrow.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtktbgbzwl.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtcnavyvcc.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtyonrerem.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbbjjqbtz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtkdwavtpd.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhqtlceb.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtjblacvaw.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtvjbqtazt.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtfgayecfi.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtnnvdskna.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtuiwlznef.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gttoofcajn.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxjbzkhbk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtbjowjdyj.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gttqalhlmv.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtjqflxyrc.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtuynuszis.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gtsdixzhen.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtqbcrncku.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtbpqtjlfl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gthpzjaypz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtcdqrosdd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtjwrllxmm.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtolndyodg.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gturkwyttd.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtsmmqaayo.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtdlibqgco.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwymklxlq.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtqzqfagiq.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtrazdjaxc.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtlhbnneow.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtosvvbbzo.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtkqerdott.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtqwirxmyv.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtaibpqqmd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtbjxjtexx.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtnldstfar.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtcgtwyjuu.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtncunqwok.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtqscchtsb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtqzhhawhu.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtxglzsnwy.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtkmpcbxpn.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfznatgi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtdnjlmajw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtodpfwveb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtgphkomzi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtiiklgtwg.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqwkwwmxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtjqnevumm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtvhdgggdr.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtpogkhnam.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtnhqskbwf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwretubbn.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtqpcguxbf.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtwkyyvxlk.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gttppebyfb.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gthvaobsrw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtxkuukhfr.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtxovqlwng.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtyqmaestj.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtimesieos.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtdhywbcml.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtiqvcvadi.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtvrpggguh.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtjzeekdli.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gthvecjgwd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtcxxxsfag.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtauojrotl.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtdkraevtz.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnivzmckp.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtuwusvyzb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtrgmwfrwh.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtlwnqffqg.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthqgucumy.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtcdgljgho.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtypzymovr.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtpemkhghj.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtclmvoqfe.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtutxzdrlw.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtbylkvlhm.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtjrhmtdse.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtgepxanux.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtcmajtqau.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtkxsiqeeh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtsjijllku.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtzozdhkfx.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gthxahaehc.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtqstsaruy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtnnimkorp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtytuouluf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtiuhcrxct.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtwpawsdwk.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtevgtrbjm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtibhigeru.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtgvovjtpc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttjtjykv.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtkttacmic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtqhblxvxb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtqpeuidka.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtphnspvvl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtdnbuaofv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtiyeqjapg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtcqaviuzi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtzjeirmwu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtbkljbzpv.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtweycomxz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtclqcnbgs.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxtpvqjb.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtqjaqglzz.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gthhpuluay.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtztzrrxkc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtueszjfej.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gttkdxbjth.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtyylnlwbv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmnppymaq.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gteiwpeuct.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpzdtwfrs.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtelcbkexu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcshasjch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtoloaeiex.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthgegjwey.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtymbusrcx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrkjaylbm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtncwjgnkf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtlshbkpca.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtfdzvnnun.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtfahtgqay.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjmdfqiw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtraaqyfqc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcipeeilw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gthdkcwsxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtyoequdig.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtbijiukqj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvyipkka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtyhsatlof.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjlgoitm.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtmilzigow.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtxollwylh.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtiuitgiti.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtskprrglw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gttxhskqhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gttaeukcxv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtsafpacmb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtrjdlxvaw.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtkfpqimsf.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtgqtjdfbv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmptjhmci.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtgiiznwro.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrsqdrdps.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtutzvvxpn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtuduvbjip.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtybekfuhd.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtxbykgbxt.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtjrjxfawm.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtrncllgup.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtrzscgetz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtdyaqcahl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcphqhfmw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtkzsawdsw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtxsosrsoe.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtfdzgzoar.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gteukryjem.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gthdnkgiyj.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtlyvfxxaj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtflhkdkty.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtudqxdwke.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtgizcisof.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtiphfmske.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtbliifaxl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtglekrelv.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gttghjjjqx.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtrxwyaxxq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gthyedpxzy.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtfwznzzqp.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtfxceesij.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtabrseibt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtrowxeuty.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtdffqskyr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtryhebixy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtlvorytsz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtntqevgej.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtbprknniu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtlacuhynv.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpezecjqd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtphflwdoq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukkhfpbg.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtnizyujnt.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtvyucxpgr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtdjnrwobm.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtagbtgpiu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtrbnqbbhk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtgznbkvvy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtyfzkuunw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtrqdzpyyg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtksdbjhhv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtjrebmlre.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkmwmsky.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtbvjiwoba.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtcscozpjy.html


<!-- 参考信息 -->