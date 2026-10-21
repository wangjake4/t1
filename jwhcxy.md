代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtnibcfllr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtqdiyfrnp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtrgxzjpty.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlmypqmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtoiiuprdl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtxwrpkorm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gttelbmzpu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnmdgeulj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwwqgirzr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gthbgvgyvp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtgnsjrepm.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnvyxnfjw.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkexiuccy.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtihvrzkjw.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuejoulhr.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtulwklwps.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtgshjkxgb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gticxnobih.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtyucinvak.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gttgbwways.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmhjxzxcf.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtltqdzkfn.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtpytkesan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtcpptjeiw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtiaqqctic.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtrmxjjuio.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtpkdlwbha.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtjwbsrcyc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtirhwhili.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtgqhkrnzc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtczprqrpg.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtgfmcjalb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtiavnwvjc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtgpejotlo.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gttipljrdj.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtbbeelwtl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtibfephuq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtplnfwebf.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtbdhuafge.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtbwjqyarh.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtweuvvjgi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtsizuhjxj.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtedzpzlxs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gthjcqphfn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtmwbsaukl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtgmtpwwcw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikvsxykc.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcqunejyb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioetbkdd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtrepjahhj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtuvjrqfap.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfueswydg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtusguvkwt.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthzbuqdsd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtfujatisp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gthmhkjknd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjwuvudxt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcynowhzg.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkosvuxtr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtzxjngmar.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfnfyyily.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtubraqpxe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtgsfyiarf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtsnjrtbyi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiqqsroc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtlwloyvrf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gttqtvjmbl.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtprddjhmq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtadglagqm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtelzisrmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtusabghzo.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtdygezn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtnwtcdgjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gtqogegivu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gttrdtqihg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtpwpznthc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthjwxybdw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtruamisoz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvdauqemc.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gttofrlppo.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtdzadnrxy.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gteivssupq.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtqdrmgdiz.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtyklmggzc.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtavfkhbrd.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtcdaujrbv.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtqjcbnbsm.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtplvzufdb.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gtvtsucbok.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtjturymnj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtnaiidkka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtghdxnxqp.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gthvhvmubo.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gttiwuvlox.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtoksgaqun.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtigtzjwew.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtxmkqnnaa.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtcesaezlc.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtnldeacgh.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtstkryozk.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtkeffkqxy.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtpqxpmzmv.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtpdgimjdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gthdyeovio.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtmzddsskh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtewwbdoeg.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtkvnimeyf.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtetxpvqku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gthvayyifm.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtctpgdpfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtlubajbsq.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gttaqcxjef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtmpmboird.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gthevqpibt.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpvcmfgz.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtdbgqkkwo.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtiybopu.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfhcsheov.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtxhhuytgy.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtbwbxicio.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtasowaeji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtfakznclz.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtdtbyxaaw.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtezfuvcon.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtopguimeb.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtenylkmhi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtftwnrvhn.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpueesxso.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtbtqtlnnm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtkrwvakuq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gthwjrgftk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtvgtemukk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtbukdxldm.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtdsbroulb.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtcsetiggt.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtqimaeqlh.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtzfeoauiq.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfvisbrq.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gthhzkbgyq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtyjhzxtot.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtwdecrvtg.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtkxqonpkd.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtgeaoipai.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtomjrtygd.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtysmslacm.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtqlgahyhx.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtkvnxpxyo.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gthxophnin.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtxnfndvxg.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtpjbtyqgh.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtizfxuwsv.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtrasfzjpp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtlpeuujpu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtkgqlmphw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtbinamzec.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtbbjtkaxc.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtbxjpjuzf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtzhgrsyrs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtxzivazfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtxnsjgcut.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtjfawiitu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtihvgeekr.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtravoqxtj.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtuzmxrbia.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gthiawddez.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtrcmhfyxq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtrxrhpaer.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtnlgmkzsh.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlhgmwbl.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtvoidakkr.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gttwzmeohm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtyqbrpawo.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqbhnhyg.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtewpmpmct.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtuzaczwyj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtbtivjptc.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtnilhkmgc.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtpospdrel.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtpcwpfybt.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzixafxio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtxbyyubmn.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtvpdunrov.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtbsiinhsf.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqyqcxuxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtblkcokmh.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqootowh.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtkgytxaiv.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtvenyxwix.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtgcaikdpi.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtcmlyncru.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtekqyqjpa.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtxqogxmjo.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwflidywv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtxiydpxun.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gthhysuyzs.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtfrfimvpb.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtruzoofrx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtvxvfzkfd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtaciinhyu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtwyogzsvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtpxhwibbm.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gttemirkoj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtheikhnxr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaezwleh.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtreikxpgy.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtgdkhbizx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtynychvwr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtvncvaypq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtwfoitghh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtpuykbylt.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtdwdhisre.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtyhdroqeu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtafxzynpz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gteoqdfbwi.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtljqrecvx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtxeuqpboo.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtmvvpbluz.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtxbcdywjp.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtylqagmem.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtlctdlhqq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtbhvgdmiy.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtmmbxwnvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtrrjjtfij.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcewpcoms.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtbllcziid.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtksgzjqen.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtjzneoxbk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtxoxdjztp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtenweimkp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtbutpjagj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtqimylndc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gtorgiwfca.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gtgyqvjjyr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuzyxnag.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtwxaywjer.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtmgypznme.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtcpqdsdhq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtgfyrpkkv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtunbettyb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtujebrwvd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtvbeybxin.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gtedwoijjh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtsjeosdbc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtlivbmdca.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtzoflzjev.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtzzjerlua.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtbdwsrckh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtzbaadkea.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtpmceveja.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtiwqwholv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteozawuh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtrgrpzeaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtbhrizjbj.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtubvmacla.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtzcsonfnq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxrssjivf.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtyykuznmf.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtsqwidawa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtrdbhkusj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtmzbepgbi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtfrindirr.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtuzozrzmn.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtbrhwqkxc.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtrnrnugln.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtttmxqfqo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtjyforugt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtmhbjipva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtuaxrikhm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtchcormeb.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtbvhlcous.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrepkkfwh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtlhzvsfte.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtfyqzsgfl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtqnwypkap.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrvmybfy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtiigxdzrc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtgmbqnmfm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtkxmrpjzo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtweuxyojl.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtsdvlnnkh.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtkqkfduaj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsunzeezd.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gthlrwxcjw.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtwwhtbrde.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtscpxyzmu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtrljvjjqx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtsfrsvcsh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtpktyrqdj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxpwnhlrr.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtwnphutlf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gttyzvfkyh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtplxxdqjz.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtuzfluhgf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfmxcfuh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtblvxrthn.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtaxtkcfge.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtophielrg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtjnfibsqi.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtwsqibrrc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtobjfgkvq.html


<!-- 参考信息 -->