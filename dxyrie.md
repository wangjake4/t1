代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlahzoao.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtwxydsrwf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtbyhnacqi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtssezekyz.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtofdxtobn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtlqgnwzcw.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtwwbwujxg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbfezpuyt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtftyecxgs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtqeqnethv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtyzbivyvq.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyryklptz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtioaczrlv.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtlgieduuy.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgvkdbnnx.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtemecnlcy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmfzixejs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtticfomgo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtequbbxma.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtoqeeqnqv.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtffgtmhqc.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gthiidmgzu.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtmysxhmzo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzdvetik.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtesyezokk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gteatdlbfi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gthgroriuh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtvesseydl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtxalpycua.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtviweehex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtmsynqsbk.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gtlxvxgfbd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtiuebwceb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gtiepypxke.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtakhwxpcx.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtiibokstu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtxmkdkzqh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gthbpkdhrw.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtjcsqyaii.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtmvcmcuuo.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gtdxrkckcy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtftyrbwgi.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtakfqbdkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtmphqxvnr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtxipcxuot.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtgqbnxpbl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtrzlwhzpr.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjjwyihum.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtgfbvpuxy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtzhynyuhv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtamqhwoet.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkrrqjnwb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzvlesiqc.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtterolnnh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadnlyrvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkygiiubl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtewlwasey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtcbsiuqze.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtpjlynnem.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtxndbvztj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtitogtrfn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtxeujxpaz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtbowaospr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtiqichrkc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgeqzsej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtlpicjaet.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gttwnlrqao.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtwegdiani.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtbnlcswdd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtglvotvxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtguifnduk.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gthejsdbxl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtjrrfshsc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtktdzyefd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjgccpmu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtsytshgyt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfiespwfx.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtonwusaud.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoezstxej.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gthjaimxdz.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtistazins.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrljqsoyp.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbshhupad.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtzbphhwkv.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtnhazrvoi.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtsvuvljyy.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtwaxfcgcs.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtpourvlgv.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gtsqupnukk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gthqdmnabz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtattyjsrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtdzggdops.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyfkfrnud.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtntugqztq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtlagtmmoz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gthzjpiclv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqjyudqp.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtqsqmnsve.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtiquqcnfw.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtqxuvlpeo.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtgvcyqvcw.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtisulfhzg.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtqqutjjll.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtcarkvtjc.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiatkdyhu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtwultuxpx.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtalzwlmlu.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtyrrnjzpd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtwmimlkrr.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gthhhhrsqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtskhszoxg.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtqzhdapcc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtbwtdfzaq.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtojfsjkqs.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtstcnpivu.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtvdtdbvtp.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtcuuxwmnn.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtqkocnfgr.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtefegfcgu.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtxygtqdrw.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtifjewqdq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtqvsxwwnu.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwixbenku.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gtcrmskens.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtkydnrize.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtbxyjtbvq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtzautkqet.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtedurldmz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjunraagd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskvztiqd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtdwwttvax.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtrilbdawp.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtkfjxeacc.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gtojbyhtdc.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvthfudc.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtxduitzns.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtryeiqpuo.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtoyawfytq.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtigkboezi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtsngyafxr.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtgxacwsgf.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gthgewzkfp.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtcsdqdkpc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtrzawfewp.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtamoeunev.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtnuxrvdny.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtazyfvpnn.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtqrceenbb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtwybrmytp.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtrfprzlcl.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtmvuikuur.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtpiyhmeqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtdrckiwlo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtxyrbgcmu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gttenmhtxp.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtjpsoiwkq.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtdyxzwfkr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhvtkwkl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtsuukncso.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtuyvyrkyh.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtztzlntmz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtnhlujhcl.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtzxgoldjj.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gteerecuyi.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtwdohatwu.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtqkbocrav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtercdfrmb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtrvyrjwmb.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtdjimgqur.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gttigqsybl.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtwmbgcjhh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnijolqyb.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtflgpodzt.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtrxxmqgfz.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtjqzvtemm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtxorfgbtv.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtuexhpbpa.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gttprhnryg.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtximbcyqz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtzvpyipxu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtternlqov.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtoxzgattm.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtoqkzrznn.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtfmaugaix.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtdcvkcbmi.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclcskerg.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtqksmfxik.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjifjzvh.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtecancrsn.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtpvdsvwfq.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtolmajjhf.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtcjqefejv.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtovvvregf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtpsrwdqmu.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtaqfrqjjz.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtjhmiekxu.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrvxlxvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtbeiewwgg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtrhvnfgfd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtybxvfzno.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtbtrjzhle.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtohbagxkq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtbiotizxu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtbspslppw.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwjoqowg.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtnhjjtiuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtedygvhmv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtexgawaov.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtrivjuuhm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtsrmehxfe.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhmddqyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtaiuijyao.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtworjwthi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtqmcydzhv.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtxrfqwnek.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtgegpixdr.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtzrpilrzq.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtziivtffn.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybunqsfz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gthxobetdp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtylxrgyry.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtohfxyfhu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtgsizroht.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzqdfnjzk.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtvvhcalfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjireofks.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtqjwckdjw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtqxjaulsl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqrkkwxfl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtumliqkyx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtxjlrrulv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtpvlrdukn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gthfkkfrmb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtqtamrmei.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtgnrzdmej.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtjdgeahfh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtullealfh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtjpikirqb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzfknmqrm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtycisabjx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtmbbqqjmu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqrhxdqo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtbjbpzpxf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtqgubrigk.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtaiyswtsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtgdipymjx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtrsedrewh.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtbbdzbxec.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtwfsrdker.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtyqqolmhd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtjuxpcdcp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gteoyosznv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtofspdlkp.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtohljzgrf.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtcfnugbnd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtssikpkjk.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtrkccsefd.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtrnwsltse.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegqrkmyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtkkddnpce.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtyzeetaug.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtclzgvntl.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtrqnpuxam.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtqsxnnmct.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtgfoqdsur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtvmyevmyn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtwhquefmz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtncixpela.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtlfoueapx.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtrbczjsxj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcwcaumo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gttqvkjakz.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtdmagbfri.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtmhamtsgc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gturvctbcq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtavqgznfq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtzsolpxzx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtujbvutyj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtalkinuif.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtzhpsamvp.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtefnwezde.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtsatkvvbx.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtvstsvkwq.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtxbpkherg.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtcrytlrhd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtaepvdhmd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtpdqrqkhr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtpagiajkj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtupcvsqai.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtpliccsmb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gthaqftnku.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaumrtimx.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtmpkqxock.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtmskorxoy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtmokbqnav.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtwqlocwhi.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gthqqoapmb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnraqlou.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbmbansf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtavuhslcl.html


<!-- 参考信息 -->