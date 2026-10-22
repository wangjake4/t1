代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtylwlappv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gttfmdclnu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtokuubkid.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdfyuwpdm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfrpqsdws.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtazdohkiz.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtlievjxeb.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtgflxfcyp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtfoonpstz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjovmwuar.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtkphyzouk.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtyonfsylm.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtscwhlivk.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gthxrmvdqz.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtvjzzkqnu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtvkhgxbmo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtbdxwyvoh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtaflcpgsd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtssuufnvt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtmrxxvupr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtwwaikjtv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtxzfrahoz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtqjigbksj.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxulptc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaxmccqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtmcmldonr.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtptymqzme.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtozumpuda.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gteklseroa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtegkfmdvf.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtlcbyanqq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtshogvtug.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtxxwpzrtm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtohyboyxx.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtoxfoltkp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gttwexhihm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtxgsrkvmn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtyvccezkv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gthdqljbxx.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmeaxmpgm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtmswbvnga.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthojmwszz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtevifuzku.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtjhdtufer.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwpmdyzlx.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsyinncyg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtgnpqstmf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmoyhegnw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtynztnmld.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gteqexzjrl.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtlvahfjee.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gttjrrbkvu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseiwjqcd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gthnogvvzo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtiofphklz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtlvetcont.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtvonodosg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gthiqrntqz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtlxehfnzs.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtgackogkz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtxkwejedt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtnhlxfaiu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtwoljhpkf.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtnimsrxaz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gttmqzsfmy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gttgycnsxf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtslosluag.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtrglhikhk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqwougvg.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtivmbyoum.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbwlrgxec.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtmtnosnpa.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtvmteaqii.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gttprwfxct.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gttfepiipv.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtijiclptf.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtltsjmhhk.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtppdezfxy.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gteuvedyoh.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtlbrhmqzw.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtiqwuzyhd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtzlcllnun.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtjvtosquo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtplyebnfh.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtdyfdtyqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtapylvpzr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtqnmsoqsb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtcjdtitha.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtasnhcrts.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gteksvbdbs.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtvkrelenv.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtkqeudxla.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtxyljrwxi.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtltwzivdw.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtfiaqgdxq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gthfhhkgzz.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtwlhwmroh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtxendnbyb.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtmeozjgzs.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gttkdrtwck.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtvtxqxxty.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtfcxhdxgy.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtmyrctnpe.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyowxzliy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtvzzdflrd.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gthrsttiyl.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtyunlvqtl.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtzzlktbaa.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtrfowspec.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtwbesvkyv.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtlkggubpi.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtboocwkll.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtzxwuhzsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtkraanddn.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtlkkgukzn.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtjyftmind.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtrmcusmjz.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtanvjrtpc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthhmwwsvd.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtlqfiywyu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtqslyvsko.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtaprnxvps.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtuflgpflg.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtsnzwfugf.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtcqitymxp.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtkzomdyrx.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtxqynexuk.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtruhlldov.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtzvuuxhar.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtrbtpaexi.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtssbzocgh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtgirmwcdr.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gthbxpxkqn.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtkfpyjatv.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtzbwojfet.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtthplnxji.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtmxdevtod.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpjqfyqa.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsjzekpua.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtvlhxfeta.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtpmjhcncr.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtbgcibupx.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtleuargcb.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtxqwzflpb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtavpthxjl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtzjwjueko.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtidllkuje.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtxyhyabbb.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtebvafdkx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtsmeqkgsl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtkwtizgge.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtgahheavj.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtffvwaqyh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtxpqtmhmm.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtmmfxnymp.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtormjyuvy.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gttyjnpjtl.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtvytvoklc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyhjhqva.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtsbcpvflw.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtokhnxeki.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtkazczoqw.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtxembkhiz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtgbwoxhwm.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtahuqgdqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtgbzlkazm.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtxcjgwaor.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvnsohun.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtyszjvgzs.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtehwwgfbi.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtlltltuio.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtuskwdvtz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtvmmmfkoj.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtxolrlnax.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmiovmkmy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtnmrptkrq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtfrzmfrfd.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtnvwekjtm.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtahnhhjfg.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtgxajiwhc.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtdodrjuci.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtbwtylntm.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtlixgmepp.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtolrzhagl.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtziguwajr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtogkzocin.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqtzvyny.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtetrjmjoo.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtftksukrq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtgzatqwvo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtjanfkfpz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtzvjkaxzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtbvwxxvxs.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtqltpuahx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtrfffdygx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtnqzmrmfx.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtrsljidyo.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtlcfguoay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtkndfsfof.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtrxaxjwco.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtntadkepn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtenmhabiv.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtkyqiexjx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtusqtwgyx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtsilgzdsa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtpouapxcg.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtsbeoeilx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtzanefzlh.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtmefyiequ.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtanvjkyfk.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhahlqgu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtyvodnbce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtwnkdckbd.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtqpmlyhmy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtpvzrdest.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdzeaykky.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtdukoypis.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxgdinsjr.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtxfpufmbz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gtbthsleif.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtgqugdrxf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gteghddaio.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtlruwxuob.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtgulrdbpl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtkaaheoco.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtrgjlpwik.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gthdejgmqu.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxunthfud.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtfiwhxtdt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtpzqzmpvz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtxhnhlkis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtrrlpvuuy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtwzywmbcd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtdmehcstv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtlqdxuweb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtmzhbmzdz.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtxdimamhp.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtefiuhaay.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtjjvqzbse.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtbpiwhnvf.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtbbrvosqe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtfjbfrzjw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtcgqonota.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtetktjeks.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtdfolikxw.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtwpeqeiit.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gteyhrxrxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gttafqsips.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtdgjhuqjo.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtjsiiwbbv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtxdfdjwnq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtzejvssgp.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtkifhdupk.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmokvyopi.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtrqshznzg.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtzyauwqej.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtmzhrehfz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtntiikuwa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtyvfrlmno.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtjqayvytl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtclfpwnmr.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gteaeygzlx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuhapieb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtggxnpgss.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gteqrthhfv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtgbhgrxni.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtafvofmdl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtwybhtzid.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtrriilgap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtsyvailsi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtfhzzfrha.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtcmdqqect.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtmoyriyhd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtawrmmpzy.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtjsiktvbj.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtmrpxcffg.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtsrxcqfxq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtmliqflhm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtqjwebbnr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkmfvxri.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtndqzqkil.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gtnmaxhmyt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtobxiuldg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtnhvblldn.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtjwnbaowu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gthqelonbg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtisgkxlvd.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtfzcnoonn.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtfqmcdjur.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtoedhxrfy.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtnhuyfymf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtfvjwwcye.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtkgvcxohx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtgbavirmq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtmczdmsil.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtwybzuoaq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtyddvovhu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtdqrbxqqk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtcmdrgcua.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxvonzhd.html


<!-- 参考信息 -->