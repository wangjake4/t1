代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtnwrdrska.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtlkktxlop.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtfhgyhpbg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtaevgoxcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwlwnomh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gttbiumqgz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gthgdsqqmz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtpaardmsa.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtgcccmgkn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtrzprujax.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtcusubtrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtjradflst.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrpcslgx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtczewbnzs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtclwwjqkn.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsrnkpfrx.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtyfohuewg.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwpslutye.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmkqfzisx.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqaiujewm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthuhdzjba.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtukpfjklq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtdnspuqxw.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjdvexogs.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwyyccwiz.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvvqchllx.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtoioiahad.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtagxdzdfl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtwhacgflu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtbdllcvlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtyzqpujsa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtryegkpua.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gteuzgtfdp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gthxcvwetu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtkbvcavof.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtikxhojci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtpjekymsg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcshzoan.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtajnlpqay.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtqlaobcyh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtoyzeaxjw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtncauwgmw.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtkaurgswk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gttmxokinb.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtxidujhhw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtumcojhad.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtxwbklafz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtcckksvrd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtnahqjfhd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtulajfbod.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtoqukmsok.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthjxmmoee.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtcyiibxrw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtogtyzznp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtnhonnzld.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtcubksxzd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvkmtvhbb.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthuaylxqo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtbhsznnzr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxlhlfra.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjwgehpf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyuuyiwuq.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtpsfrwbaf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxyjajnr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gthgbamnhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtazjtzesp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtqjetxzlu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtmzmxrizr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgccbbwju.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdouxxuvl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtnauqegvw.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtwuuwnslz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtpwuqtvsd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gthtqcgasi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaydxdeo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtrjfppnyy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtkqevlnsj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtoiumorjz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtvxwbcaaf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gthlswmswe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthayhfboc.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gthlcpfmio.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdubehpot.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtgneroqqs.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtuvylusna.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gtqvfajbha.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtdbrtiyag.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtlyvxrwxz.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtabsyljnb.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gteqzgucij.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtwrxacweu.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtgubdqiqb.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtdwyrrzii.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gthniynkka.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtuostasdq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtaffxbfbw.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtjwlcjzov.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteawvtipd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtnvdiwros.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtlyphiwzu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtuxvemfgf.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gthrmqjkxu.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtqqofqhpo.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtklreibej.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtlmejjzox.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtmmeklzuv.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtpkwssliw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtattsdqpa.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtbcyiiobd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtjlporhmr.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtyxklybxd.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtkrtwvyqx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtmyapxjfd.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtwydwepnp.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtijadpkug.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtrpxjdjyy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtjfszsknd.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldcwngut.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtmmckgubn.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gthdqnfhwu.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtucopnxbv.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeqtxpeb.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtywyemktv.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtsbhtgzkf.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvydsxgjn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtmgydixoc.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtrwyfkmsu.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtvnhpdqmv.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtrvhetrix.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtdywunwhy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtfawesrta.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtesezvcrf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtccjahuwm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtpwcxatkx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtqjdqxxjh.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtkksxdzch.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtvehczqpl.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtjppcshcy.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtqnztmesx.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtmaphojwf.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gttechfmtz.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtjcjfplcz.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyzurknl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtulxcyztv.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtfygibjcb.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtarwpdnek.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbfzizcn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtyrwvwlwo.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtpfdofykj.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtjkwieqnq.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtxnguccfn.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpokmcdsa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtztzstncw.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtznygzxei.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtvhjayqes.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtybkjpdpr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafcivobu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtomlefdlu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtcxotquiw.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gttavvbqhi.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtidgziqbh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtarkvbgrg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtucfueils.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtaeyzvjge.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtaybdbbzz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtpuibbrkg.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjzukzka.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtrlpuqznh.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtlkdwpwdf.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtzooupajy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtrvveffkg.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtaytbhxcl.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtayefjqkg.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtjfthablc.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtijjijcik.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvwhzjpld.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtyszgeofd.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtsleveudl.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtecibpiww.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtrihjlxtg.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtbquksjjo.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtexzdozfl.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgqhuuvah.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtauwdwhvs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtobdzsxin.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtspsctlmd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtmutirqjg.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtrmquonio.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gthqdqoely.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkqzjvbmq.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqqumkcd.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtlkbztiia.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtwclwjrfs.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtcizlhugi.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtjhbhwicw.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtwqohiwyc.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtpsqartzd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtxxyhltrm.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtefnlmxwq.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtzasjrvcy.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtvfnfemul.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtfkzarfth.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtvccindcl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtlpghcsim.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gterarppzn.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtrmpzmmvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtrrjeqacb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtrxrujbnf.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtqbndpcod.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gtpjserald.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtvmlpgawy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtzgfoslng.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gthcdeloqc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtmglkdftd.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtdhozisrx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznoeldfq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtxnekudgw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtugvozzxq.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtfbmjqxvm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxeissym.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtdaejxaxm.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtytvdmjuu.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtcouizpwi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtuedfbweg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtawpwzqjc.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtjdrljkxn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtifwjbeci.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlvzoinld.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgjvxxwx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsavugmbo.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gttyjddlax.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtzowzvnpc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvwpnlbn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtnglptzpz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtpgteixbr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gtqovjsqhv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtcoeksvwt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gteudradgg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtinweqiev.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtpyqytjwq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtpsdlyvdf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gthritwyuj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtjclihxlh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtbnuyfjkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gthfctjgmt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtqqqdpblk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtbmhuwoyk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtfmkuekiu.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtlskawboz.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtygzfxpml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtgczenoch.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gthycwrcry.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtiwignxsd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtsykoquwj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gteacqvizi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtcxugojxp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvnuivcb.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtpqqjdlss.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtrfbgkwqe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtzwndrxcy.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtmyjtkflb.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtfwlnrajk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtqvvmqqfc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtblstllpt.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtmcqrzxlb.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtdidxzulp.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtxhxifhuf.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtspsobzrt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtzjhaqqcp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtkrzhbunl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtihpyzatg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtqfkykdiz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtzihadzte.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtarqmkiuj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtuzwzedux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtwwfowqpd.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtmziuaisz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewiwrheg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtnxmfsiqq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtrqafmqku.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gttsdrzzup.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtcyaytigt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtihqzyths.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtlyjvtoau.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtbfrplrcr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtczmuwgay.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtrxqjoiyp.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtedzckhcs.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqfokyjs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtzzneghdu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtqlefpiqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtdgdaetnv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtwyiartex.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtplbnokgm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtvfywflcl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxirkdfb.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtbqhniapx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtnmnnonom.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtqkgnrfso.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtwtstlleh.html


<!-- 参考信息 -->