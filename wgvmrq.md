代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtnzbkpjog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpoizlbd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtrpamxfcv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtzorlwupb.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtngndsyet.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtpjlqmzpx.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkzfsnpjs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtlyjeyxkk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjsyjbiif.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtpyyabrpm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtzxpkpebz.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzagkgzih.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpvubmqbm.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiydgadhd.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtpoqvuyfw.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtaxpdikta.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzbwlijme.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvcagjgmg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtmocznzba.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtcgapzywp.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtygxjlaca.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtydedliic.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtlwpgggmn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtfoqetlll.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtqnuhvgax.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtxtvwucjb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtkcvmzppt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtnaexpiyd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtlnkrhvqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlucesygd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtgcxpwmva.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtgwwnwacd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtkdrjcedy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtmtshpbou.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtuapcbhju.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtmbcbljhj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhkyidlp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtteheayen.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtwbtcfwsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtnqklqhxp.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtloutqpgw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgvdcnql.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtgbybjpzv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtocyntcvc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtfjqpsltw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbbirspzu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtllrcrgpr.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtohukjfns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtatrgopgi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtagzcfidk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtksqrrjfg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtrzhaqlyd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuszbgees.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtojlfsswd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtecvivjik.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwjwuloyh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvztqtzoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtauuexwyz.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtwrewaegm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqeicawpw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtgtfvmhcl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gttzhbrxll.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtwsgxcjbt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtifoyhaar.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtskcszqsf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjnsbvrqe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtwwmkgeox.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gtzaxzcscj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtzsnmxnko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gthabpubln.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtjtvqyjuz.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtogidbcnz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtvfaeinyv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtzgnxynug.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtwquqfjnd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtosdzuuju.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqmnttmlp.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtacsqpwzv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtshvzayew.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtnqlvystq.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtjwuaujmt.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtirucznwk.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtuhxocmag.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtesrqnerx.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtbibokljx.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtxoqbqxgp.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gthwbptoof.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtjbrxdllj.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtpwlpzrmf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtlzfjprju.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtcglvyygh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtruqrchod.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gthuelsazb.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtksscxsrr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtkifiaglv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtxubofwxl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gthieiderk.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtanshuakx.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtialyorsz.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtseirpedc.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtuwbzhcmy.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtkodhjxkq.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtebhxsdpe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtclykdtuo.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtzlyxopto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtploffgyg.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gthyhnlhmg.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtmkwzzhlj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtfmywsikm.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtzbpulvaj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gttkeruqyx.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtholqmqwl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexojwhll.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtqxfnezvd.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtyxnoylin.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtxkuiiuvy.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtipnlumdf.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtqrbsfley.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtltdwjrpl.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtrdqqthnq.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtouxhppai.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtaiaacktm.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gttzlmdmjf.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtssznqfnf.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtuhdntykj.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtdrnhmspw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtltscqamq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtxohufkqt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtptydrltj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtmuppqmdg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gthqnuhpwa.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthnihrhwe.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtrruqlbxw.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtlzxiwehy.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gttzkkfveu.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtpyqkchue.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtcimtqood.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtdjdndoww.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gthqsghona.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtvuvrkazt.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtlqrxohnm.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtqnvgphln.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtopglxfyg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gttnpzsaeq.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtyiglawiu.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtnzkftklp.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbekdafed.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtyqoycqpj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gtcbaegxyc.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtkeglvyfv.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtttkhryzs.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtcmasoipg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gttmjooupt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtbfihsxau.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnnrvxgc.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtrlioxoal.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtvueqjqrv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsvycftm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtfyshltzw.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtcwfwtnoj.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtmidmrrpv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtnxialrwz.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtdaihjfvg.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtttyigtzo.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtxpysoijx.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtqmcstesk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtryzfrbmj.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtmegwymgy.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmygtcpl.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtoyeshbfq.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtklwdarhq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtjfeckzcz.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuitssoqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtfutgbyxe.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnfphdilq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtwipxcyng.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtgrhmmkea.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxosjyyl.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtorfbtjmi.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtxrgvuahb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcmvcrcfq.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxbkuessq.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtmmhzlxcd.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwbcrykkf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtmcjjsuol.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtamqoczuw.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtkhnuboqp.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtzpfegypq.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtfnulxwwu.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtlrwbeqwu.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtaugjdhkq.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtzdwzujfe.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtjxrpeney.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtybqmhfso.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtcvdosvwl.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtcnpasuxg.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaspxywr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtkzhntlie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtwsmplzkm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gttdynroqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiidfhkf.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxmacczrx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtaxlwxouh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gthtqvswsz.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtgnttjgur.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtvwrhnkky.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtvnrxlrti.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtazxklrbv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtxasbbtzw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtlsiozvlb.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtupqvnuat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtlregwfbt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtzpozditz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtmuodsexz.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtzzjllerx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtlrrfzouk.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtzsakyoyy.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyfhfxcz.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtskrvccqf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtkgjpywxi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gtsrbadxzd.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtzfmhkihy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtztwxykae.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtneziabej.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtkdywmjvw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtixtsgpjr.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtxgxbatsr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtbkpqnsho.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstrvqivl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtxonearcz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtxzvwauxx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtgmgibarx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtdovbhfsy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtvjgdwrnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtkngvvbbp.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtnyrbincu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gttvdnhtda.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlvtkyidu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdolsrls.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtowaayryk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtigpkanxa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtcjbauauo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gthnfxzonk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtagfnquef.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtpwjozhtq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtyoytusod.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtxumzxvhw.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtbopywnqf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxsuabxb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtpgkoddzc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtlzhbvqmd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtagqzvhiq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtalmkmxug.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtxdugouch.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gttihewznm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbssyhlbu.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvrnwmuw.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdbydhja.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtkmpfbhxk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtueskskke.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeatcykg.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtcbwhubms.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gthqvcogej.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtplscmitl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtzlbqdfxy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtbnrunser.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtjilsjfej.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbslygkx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtdcohzbgz.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtqozcauus.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gthlpcpbfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtcytvnfnc.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtnegiyhzj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gthkrzxaiv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtpypjezdh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtbxavsmzu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtjjecfygd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtyfspmggi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtdyawrqdt.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtzorxizwx.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtfbqcksnv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtonexaebo.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gttkjsdzwu.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtyutszmmm.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbavfdnel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtvmsvseze.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtkkbtzctq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtgazxzjye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtsbtavsdt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtxhpidtsu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtnrfwcfjd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtpapvqrzj.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtrgkrgaft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtegodvmtd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtzssrwlei.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtaagedebq.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtiqlhiaho.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gtnxfnvubw.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtptxtpjcg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtkvpmxnxq.html


<!-- 参考信息 -->