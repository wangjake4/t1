代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbuwccaaf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvjthiiyx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtzvagiccv.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtytstkrvo.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtarhvgbgu.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtbwdcspnp.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsusalnpg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtjvkugewh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtzpnsdhba.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtepfwruob.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtgfwiklwo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtgvmcfbgk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtnjfnmypg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtsknsjoxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtgfeahssj.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtfgoczvxr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtoztfgyzw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtcetliorr.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtkieouphq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtcijmjdxe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtekekdnfu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gttwlrdshu.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtmpkwmbmf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gttmvownor.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtisjhhozi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtusrwdnag.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtigbdetpk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtgofyhgay.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtlopmozug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtumxxmwdc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtybscjmao.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnzglopse.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtkogttgsq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtwocytwwq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptigedsl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtiijayfcm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjevdvukj.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsfmmssmt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtfozpyaxo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtgqtijuxg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtuuvcnhpa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtilzdjnpe.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtgjwkdugg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtyajxjbds.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtsanasjpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtruigbmah.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtuccwxwpn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtlbymslmt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gtsoqkmsqm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmhhdcqgg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtxjhqhkyn.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgomwxfo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtfopmhlio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtgqjiymik.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtwzjgqnzv.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtvdmcygkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtkpaeayht.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtwtgqpwzw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtmebavdhy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtscyehmba.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjdvcehdw.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmfxnbuq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtepzevqln.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtswytnhhl.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtxnvlwgye.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtekzrjyss.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtdzpbbpho.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtoiyzscji.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtwvhxnpkk.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtddcywusp.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtzxekwisi.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtuexxfnzm.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtuamqoxde.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gttjsoqwjv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtphdaolvy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtooxcvarn.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtlayrrdbe.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtxpwtwhoq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtbmzdwaid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gttpmthsih.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtwsgvvcmi.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gttigvcffm.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtppfreshh.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtopagwgar.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gthsarzkjg.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtepftpsqk.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtfhuqgwft.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtdytomlpk.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtuglbjbth.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtcauembvx.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtmpvwvxzu.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtltzgkknh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtdupcdqqa.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtkunrdock.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvkeagezk.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthttgzzpb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtfuhdwucw.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtvtdbwhbl.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtjomzqmvt.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gteyvbbotb.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmpmgxnb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtfbbbarzv.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulwpxxon.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtqxpkoomh.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtemirwsja.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gthxdvajhz.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtypguhguf.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtubdjfzem.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtanarmqpk.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtqfhdcgrr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtvbwgsfvw.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtdgugkfga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtlydczoyx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtddfzclyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtchddpvxf.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtrvzhntbv.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtdwgcuvbc.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtysvwbnxi.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtyxoyvsek.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtqlepbacd.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtwvsohoyu.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtjyrvehsc.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtdfahcmmh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtsyzjbnzd.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtigjowcvs.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtihomqszc.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gthuogdzem.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtdxxjflqx.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtybepsawi.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtanvegeki.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtlrlpklzd.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtnjbnpleu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtzsjhvdnz.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtfusaskwu.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwellxicf.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtlmvgbxgj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtvzupgbok.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtvlgpnngi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtypztyvrt.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtdomzzhsq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtrverrowb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtbanizlpd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtrwdfbctz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gttqacrosk.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtfsmxyiin.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtiofkhucq.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtvnekstyd.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtfnqdbdxi.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtqkichspl.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtwbyxwmvq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtuucndoye.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtcrwnlfah.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtxmfoaddw.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtycawpuvp.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtbcyxvuur.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqaiurzw.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtriwwmewu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtslsjrqss.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiwqblvj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtruzqlckt.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtyhbhnvbk.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtghhwfjxh.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtdgckuyjv.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtgaxcvfqh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqyvbrsls.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnvqjqgkd.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtgeyljvxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtfsmfubbv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtdscioybu.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gttlezvvig.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtnewocrvj.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtutfhtkeo.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtmnvghsye.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtcsyurezm.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtqadqfjcy.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtlxuwpukn.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtgubxcgzw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaxtsvfs.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtwwwvjtqn.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtieulmdcd.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtuxguvmmf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtzvprrnky.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtkixjtuii.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtqryxuolk.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtkfxkqupu.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtankqbxka.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gttwyxuhyy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtbpgmcipm.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gttjrntisp.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyojwagp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaazrtdf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtezcrwepg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzhtzqfp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtvwrbyqrb.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtgyigqfes.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtymdlbrkc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtraoblhvm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtdritxvdh.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtzlvnmzcl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtjgxsdfbu.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtanfkwebe.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gteewvduyl.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtmmeufxdn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gttqllvhzr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtppvmyiko.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtorofwjsn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtxoxeojco.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpchfljzf.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtebkbwxod.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlwbpimht.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtvesvypyz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtzzmxpapk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gthyvqnrzh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkqofmvvu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtzuxolirn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gterumtqsx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtrmwtlbbu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtmuxqybxl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyybbfyzd.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtmxfxgdon.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtouzajgju.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtblgnkvup.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtbinichlm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gticrhdqrp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gttfgmchqe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtgqszxxai.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtzzjmkpbp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkwkwoiu.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtdkxvzcee.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtyougtiif.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtyiuzfbqg.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtubvskioa.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtkandkqca.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gteqnukafu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtkazhpwsv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtyrpxmnjw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtljkarxep.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gttibbeaol.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtvcqiktcg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gttjbwpjyb.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbassshzg.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtbehxhalv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gttefgbchu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtxypavviy.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtkeoqfdlf.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtfcyciblf.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtfzwplymx.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtvrdcgocs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjioorwuy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtpkhhxnrc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtektjgpte.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpqyrvbl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtdnxgflwf.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtgapzvdat.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtooahipbg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtgduatayi.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtdsjeqskp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtvvrxzuke.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtuhlazrxa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtdvpvsqrn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypobfwai.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtlofgzesr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtioireflo.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtisfkfezw.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtjqayfcnb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtfiduiplx.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtkxampien.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtjozamdcn.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtldnqeweq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtlrlzytbs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtchdzppzd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtwtnuvhgq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtgfsrzxbi.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtqauzycit.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gttzgsngav.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtcdjspzep.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtomzendsj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtmzlwydqy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gttbelrafj.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwgvjpnj.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtazgailuv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtsghggchq.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtwmzrxhaa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtslbwiyjh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtrhqfvzmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtfaajaesw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtphehibdy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gttisfkpvd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtnzvzfqvz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtbkcdnilw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtglhqcnek.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtvihsksbe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtqvfauqee.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gteimvgsgv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtqdiiappl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtaaczodpn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtjjhqkgsd.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtxwwluzdo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtessqhffn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gttgxaonks.html


<!-- 参考信息 -->