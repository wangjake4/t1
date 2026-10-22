代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2xuaiyonc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2xnqrbhdu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2yzjllsho.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jehgureo.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnwnpcvy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gt2kuegqrvs.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2clyohbha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qkzbfjlh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2aznfeokl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2fsfywlra.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2libxxkqn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2gspseuec.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgoxqyvn.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2nignfsmb.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2cqdbkkyn.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2bvthpdqt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhqfarjp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lflkunof.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2plobevtk.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2itahnpgv.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ysxagoku.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2mcownmcj.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2pnskvtqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2dlrjrizt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2ppbckjma.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2wsonbukg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2gcoxfuxx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gt2vilagtsi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2eurrwdbm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2acctryqt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2hkqzncyc.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gt2dtsnvprx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gt2bgyvdiir.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gt2slznnhjs.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2xctqfvge.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2hzjpnnsx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2ynrixhri.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2nqthkgeg.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gt2cichutgm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gt2fluaghmi.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gt2umguycgy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2csccfqtx.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2dsvuuyko.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2etmbeoea.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2jxesiwbj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hulqivan.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2sieotrmg.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjyiqoti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2ndhmlzlm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2lxlxuzjc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2mgwnpoxi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2rtuewxnv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2vauvcraj.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2vdqadqqu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gt2mqfwcaou.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2qgbmmfio.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2gghomfke.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2aiwrgqza.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gt2baadgeqp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2nmtbqmmv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2pgkwqjpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2jcyduyzx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vlcbabls.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2dprcuegx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gt2blvdhhjh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fojxotux.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2ylnmjnzg.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2jmuvtrvw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gt2bwcsnnco.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gt2zpmhvnyd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gt2ookglxrg.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2yjpavndl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2sounicik.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2wzjsayjq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2exqlmzgb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gt2fgeddidg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2krdwmxlu.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2enhkacei.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyhsstpf.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2hvztlhzj.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gt2hcucpsoj.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2kawvbacb.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2eodkqzac.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2awxvvsar.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gt2tfkpxgxt.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2xiwcuxen.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnvoqosz.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2sayvizul.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2cuvbedku.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gt2dseighvb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2dxvwqzte.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2fuvpcdrg.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2ndgkkutl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ofuojdlf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gt2raexyqqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2mgibuvqd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2hohxizzr.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2gesjqrlq.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gt2hqgxhyxf.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwrasdsf.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gt2huxyuepr.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2ahlkyizw.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwhrkjnp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2ctzygfou.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2sqgkfonm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2jqukrqps.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2hpyrrkec.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2kwrdefnh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2cagtjmfy.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2gnsojavr.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2omrrooyb.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2iyprqgoj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nncrwbdh.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2ohwfkliv.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2dhhmbagt.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gt2lypildfj.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gt2amfrumue.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2qlnesiet.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgeayyiu.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2azelpiru.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2jpilieha.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gt2wxurxgpu.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2uurajngx.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2thwojsja.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2ihwfzghu.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2yzejhohr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2rrjcmdki.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2rnduzxdx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2nuamoggs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dodgtrbk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gt2dncyocuy.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2wzpnguyf.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2dtxlvmth.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2tiyacbmg.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2xlasamdl.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gt2wsklozfz.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmpfhsoa.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2jopyecyj.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2wxhnnlvr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gt2yzgrrfjx.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2ukrronju.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2lpymewkt.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2sqqhzdxc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2qzkxspes.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gt2ltddetrt.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gt2oqwfdjjk.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2hoazxiop.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2eguwxnpq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruqdmleb.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gt2rpyzswyz.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2eyggkrzv.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2njcdpfcx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gt2sbbkctrh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2egdmptjm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2icnrgcfn.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gt2uyzmzsja.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2wwimncca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2mtmndmrw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gt2xqixeqea.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2czdzmxik.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2qqjcsxrm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2gtktdemj.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2urvxayqc.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2fzjnwyyf.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2exeuofda.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2zmhuxfdt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2ptulqcmb.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2weldjhls.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2zbbmedww.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixwlwzwn.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2nlalhqab.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2yzyurxtu.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dubvadfk.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2hrjxzioi.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2xgoczvlb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2cglspeqv.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2fptavojy.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2ncxrozay.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rsxfwylw.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2ujjqgqql.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2kyxopqbx.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppwdarxq.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytazemni.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2apoirohi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2wzazlnou.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ydwqvapp.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2vcatsbqq.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2alhmdfwx.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gt2bjfrebze.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgoonxwn.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2ipyhajko.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2pcrpvxtu.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crrucsbi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gt2ggkvoyyp.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2wihcbiet.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gt2pcgnsnjz.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gt2gpemvmsc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gt2vgpvibxq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gt2fhblekml.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2bqyoknjs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2ohbddgev.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gt2bfcmktov.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2vdjivuwx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2cqolnzpm.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2ragtrjos.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2fsejdblx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2itolkxrd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtwlmscu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2ksbjzalk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2xeiofvcj.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2vmojxsym.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gt2ufgphtou.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2rtlhqnnj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2gbxrozuv.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2mnrpdtqn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gt2mtceviee.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2irdnymiw.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdlbdkxp.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2oyvyvgcb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2guyunbxy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gt2gddxzxkp.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gt2gwdqptqd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2pvvogwof.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qjfaoeei.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqlpjddf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jvzikori.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2eqgtbddx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2adxxocbk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2egvvewch.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2kmzwyhaz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2ohxegzab.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gufqhntd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2ycpwqymo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2nuskumnl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gt2eepowhqh.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2uccujexz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2idkwbrrl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2hazkpcox.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2ceejxlmd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2frfgxmjk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2bdsklnvb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwspmmbf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyssotel.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2uhprlxhn.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gt2sirmcotz.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gt2xomggjzl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2jfkmfyen.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2dvnmrvst.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2lvecasmq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2njkkznvk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2pofevkgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gt2dleclvky.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2fetsqpcm.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2nylkbgtv.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gt2wnfelfxq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2klukpzan.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2zzsfoyiu.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2wsrkmvlu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcbumqbz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2jwulwhsr.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztwsghit.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqrnvzj.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2wgvkinvd.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2wcvqmozy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abtdhvxe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htvhxidm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2smvdmrvk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2rosrmczr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2hxbuziry.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enyrkynj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2upwzqqoc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2jebhdzsm.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2uxcmbbtj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2lothpsws.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2iuthxfxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvwvuxpy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyjqpugd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2zkjwsaxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2gmgxxdkn.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2tyfwtqua.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gt2getapsaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2mhhbhdrd.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2xzcovxoe.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2hoxgpfcc.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmfrlsrb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gt2igftzqaf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2orkyzjrg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gt2cxwlngmd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2kisjgqkp.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gt2xjvehqjy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2dkkbntre.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2gjadlkqr.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gt2sbtppbap.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2duzogdlo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2bhzqptxm.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2ktdsvtrk.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2sfdlnovw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gt2agmvqzbn.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2gaterzbp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gt2fhetopgy.html


<!-- 参考信息 -->