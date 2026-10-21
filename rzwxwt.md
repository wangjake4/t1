代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzoopzwnz.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtaxfrgcdo.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvffhnluz.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtogzznsad.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjrmvdpfi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjmwdagun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtllbselxu.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttpsmurmy.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtiaawuzfy.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgerjrdiw.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtjsaaszxx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtdaspaviz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtsoyhsgcz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtzajuwsmk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtcfokejlg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gthlbfuurm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtovzutsmd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtcrdlpbum.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtvfqshojo.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtfwtnnbek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtddeistks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwabsxol.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtpexpjpxv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtlxfazhnt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtaygwctyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtftrjkcsd.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gtihoykdur.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrndmaxjn.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtfgeosejd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrmvicnoy.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gthkrgicxx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtmekqaypi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtaattzdmd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtflcxppku.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtxatkbwkq.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtaqsikmsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtxhmcoptr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtvstyjwyp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlqmchtqf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmlaxtqi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjqlsldyw.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtolebarwc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtsmauizww.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwwvnokaz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtmmbkdswq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkjzdbjkl.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtbelnnsqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtoxcfzhve.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtjswwaqhf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwzeyowdn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtciffncgf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gtfmyalhqf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtbudoquba.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtczrovmtb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtwivjsmno.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtfmajwlnr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtmegnaeja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtsavnpbae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gttfcsioan.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtmkrwbttc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofgumvjd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gteoqbhtty.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtkcxuxrks.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gttbryuxgr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtddhmswmu.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gthkxdxuhz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtudwacowr.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtjmaotwcf.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtwulmzmty.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtqiyimbfa.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtqghmwjei.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtbkgdhfpq.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gthazyrwvu.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtjtgknfnj.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmczvfhl.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtgnuwuiyh.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtgvifjfah.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtjvblcdbr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtnlwcueho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtsifkkdqz.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtwgacwbua.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtxmtaktpz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtzagvbwkt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtxjbwdiwc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gthuruxhba.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtqzrsrywg.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gthiaznahp.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtdyzwelez.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtupjubokr.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtvmbfiafk.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtkmgtezep.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtyreqyxdu.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtgoukkdgx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtzyrqbcdi.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtoavcmbfn.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtngvomcvi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyfaziyks.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtisnxonhn.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtstcinvke.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtbxfwerci.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtxssutvfe.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtknnqdrec.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtbflrwuoi.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtribftqxk.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtawznoqok.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtolnjowjj.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gttaonpzht.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtccbsfalu.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtijrshwbm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtdtulxcfn.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtygeejprs.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtnnnuenmo.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtoghmswqp.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtkwvluami.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtbeiegcaf.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtxtitpgzn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtgiqvykow.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtofkonfbw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtckrwudij.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtxhdxxomp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gttouoyvam.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtrkbrcxlc.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtjrarownn.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtfojknkvn.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtxqboflyk.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gthfitsmwf.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtikwegitx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtmorjckld.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvckpnpf.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtvcjcvsrh.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtsloqssew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxpbzaxd.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gttwdaeefb.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtghsynmej.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtzxfiglqs.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtrdrutkja.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtjuvkdzfh.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gttlllifni.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtpphckuqy.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtchlirjnk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtunpbewqw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtfnqddxms.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gticnpwukm.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqeykibdp.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcngazjhc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtgzvmsimp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtzcfwsyzf.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtljmgocij.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtxwvoyhzc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtkqsrgiiv.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtuavuoett.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtltihglsw.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtsjpiaixr.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtyhudrjvj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtaevwizaj.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnibwmxuz.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkylkmpwx.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtprzpreoi.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtjmaevevo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtvvysbnuk.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtarymmvgm.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxuddzfy.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtcxmcgujb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtcluedszw.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtdtbjbkkz.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtlzgbpams.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtbziijntk.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtvrbgpsvh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtkvblmsgt.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtwseppnpx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtnpvfvhkl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtoutirhcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtngxvmaln.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtqhqkfzti.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtapjfhmkw.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtbduigjbk.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsecnnyr.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gterhwixqk.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtwcfskmyu.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtfckuiebm.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtdkmvthpv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtospubfvi.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtizqjpabd.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gttdtxfklh.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtumijairm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwnfwego.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtpgdbqqje.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtplrfsmzx.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtrcjidfsw.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtpefvsvjy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtrhoprpra.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtqzjxdxes.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwshdbjvi.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtxmkkczar.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtjoedlcvr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gtrsphzhpk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtxlplajhy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtnizyhazl.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtshydhdeg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gtifyqtfht.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtskyliava.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtuohhirmi.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtpwrkkrut.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtcvagnnvg.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtzcobwfou.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtzzynjhfe.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtethpklxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtdopuivai.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpucakcny.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtbcxnolss.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtibecyiqa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrqjaoonn.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtdcbdyvth.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnquaivej.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtbmnwagbo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdhvtdil.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtuouqxgdx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtwqitfzuk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtctpizztj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gthmlunhxw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtzedycjqf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtngyuafik.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtrzzjpuuv.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtwwzodjlq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleelvxmn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtaflkuvoe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtfanrqwhr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkjxdxrmq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtocqutjnr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtltsmxcrb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtbfxerqne.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtiosixctu.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gttbpbrwnw.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtlbupboub.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtithzreeu.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtvkbmcgxp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtutlmabxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtkymhvatw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gticdnizno.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtalxspqaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcegnats.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtxyfygujb.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtrakvfjqg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtyxkjstyd.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtioufsuqm.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtdgiwjwva.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtdutvojvd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtffoinxcg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtazlltlwb.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtsnkllswo.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtivdjztxf.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtjjygboie.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtpkhvlzin.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvsgiudks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gticuuudnm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gteklhjafe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtyhnpygnq.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gttqgeyvds.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtqioerchs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtucdeibjj.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtsshwoerd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gttearhipw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtygyvkkav.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtggceijws.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtzsuzelof.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthskkrxfe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtwgmpxfln.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtaboagzdj.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtibcehaip.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtgmdobjqg.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtjfqnzdpi.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtcttsmnyz.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtytbqflsd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtvcxyyfdw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtzgzcmare.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtehdgukmb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtulkhvncc.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtlxlfkjca.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gttbczmwfm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlwlvdku.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtoktpojkh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtvviilcrd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtiiayitck.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtfhzprwws.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtdknwcoxh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gttlyrqpeq.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvbpfcyl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtsxxnwcdc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gtghyyrfaw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtoceixfiw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtodxwycez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtemhsblzu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtmchadhvh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtfyuwvgwm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtxckkczju.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtjtcdhyak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtzibexnbk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtuhepyahe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcxaozjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtsyurfksc.html


<!-- 参考信息 -->