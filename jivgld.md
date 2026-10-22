代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gthcsstlkb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gturayqwep.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtjjleqjuc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtbessgqoe.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtyoeqihvr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtvjmmyhwd.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdeouwfbj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdokmqxxz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtktnrorsu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbosoetzy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtguqxgmcj.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtipiipszh.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdmvfvtlp.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gtbnjaxuup.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthnriyniv.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtlwvytomz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgtqkvwmo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtszekdwft.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtqpoiqhgx.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsohdffpo.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthecpkqdb.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtdcdgispp.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gttafoumjk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtzursfntp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcokjtcle.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtwigbwreo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtqhbmprle.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtcvkhsfda.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtatxfjxup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtuhqztnja.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtqowtrkho.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtogemmxlh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpdermqn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtfvpazenz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtodvnphwu.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtdufllopz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtyoxijsgy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtnxwpdzcw.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtxpijhjae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdsxeohrp.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gthxkhubwb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtujbapiny.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtlfparurv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtapuohdrg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gteufamsoc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtkkupcvgl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtyskwtaxq.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqlyhayrw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtfdhdpxyb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtznvjdajp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmbyrkwjj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtzneotojv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvqopkso.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtqyawdgjn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgyezdns.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtobtjdwby.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtawwbcskq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyztklpw.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtgjsqgpqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtcuwovkne.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtzhofjdgf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtgbmtxnwl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtffjlzapb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtubdzwqer.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvythotv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxvznxibv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzvlckwmz.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtajntfssz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtidblbeqb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtjdxfrpxx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtljqettmw.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtzfjjnatp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtmbtqriyx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gtatamfljm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtgvopzekz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtgbmuavrg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgarktevu.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtpaceskty.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtygeplmbs.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvwachcv.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtgikvdpva.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gttvadvspt.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtsymlvxqf.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtpcksjafl.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtubqxyuvc.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvedualp.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmfgzrlg.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtqxvlughp.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtyxopyljg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtwpvwecdc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gteuthwxdm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtwmywnbcp.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtnnknxqze.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gteblazizw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtolmupnze.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtraiaiqex.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtcrkmanqm.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtbzspbrah.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtvqbvplgg.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtewfrowcc.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtlkxynfio.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtnfrggdsb.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtaalsnocb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtqlpokmwo.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtsxmgghlm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtltafodnk.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyrpvwws.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtothflgnd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqzpqmul.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtphtzjvoq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtnlqmufsn.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gttqsqgumc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtenxadzgp.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtsejncyik.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtoxaqijyb.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtlkwlaali.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtrovhiwgd.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtvqhirzlx.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtkknoejpg.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtiyvrxewi.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtqasdarsf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtatqsljwf.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtoxxagddw.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkxmxsvvh.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gtwomkyhqi.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtysbirvvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtoshrfdgl.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtdnszbzhe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtwhwgivuv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtpdfjwnyt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtaeyoutdg.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtryskohix.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtlielneup.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtmhwyvydi.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkgbnytw.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtzdcamupd.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtdlkauewe.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtfjuuvwkz.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtgvhstzca.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtpifimknk.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajesjely.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtpxidzhcn.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtzufqmqwr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtinnsqlze.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtchkiuzuu.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtppmnkgwm.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gtfabbmfzi.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtgxrboxzj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtopzplmen.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtuksnmahw.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtudstjptv.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtvwsqrtff.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gtbgfgoads.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gteftmtois.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtducvskrh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyqxcwlt.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbvtyavh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtsorawcgz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtyiutjwhs.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtyxocnsfo.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtgrmcyacw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtabuagkdj.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtmkqdcemy.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtqmeuwjoe.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtkdihcysg.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtnuvihqbo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtmqbqswdk.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtllpdbfku.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtundgjamn.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtrxjbebek.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gthclukhxw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gthtzpdbrx.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtexxlhamd.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtlzkcxdjv.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtdjdkvqzu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtbmxfofpj.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtrudnuvan.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtivxiumzq.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtjcoikcnu.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtpyghsczu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtxnoqifnh.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtczsuzilh.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtxhnewkje.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtwzasrmlt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtexoqggsk.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtnvabooit.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtqyvickng.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtsefkgbvt.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtealhdnso.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtjzbudrva.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtuxbbrjoq.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtbqktdsrm.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtcrruvfyf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtivrqnhad.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtiljunrmx.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtiaumtmes.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtkdxspfvw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylslnhpq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtzpbvryge.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gteephhcol.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtwanjkmid.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtyiknawzd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtwicklurn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhewypia.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtlxlxxspk.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtsczlmfkr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtilkbbwuj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtalzmzmzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreknhgir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtwngvuauf.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtblnyrrkk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtyqphdksb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtpajjsdhj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtrxussedr.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxvhdoqb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtjbeuzqfq.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtniekgkcs.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtyjxippyq.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtvbjroerk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtygvpxgxd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvpwjxjx.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtnfjjvgkm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtlzzkbcyj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkjycnosm.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtnpvzhzst.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmrgyxeiw.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtimquvlnj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtjutanoha.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gthckzdehk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtfkunmotx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtaycdzbmn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllxoycfq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfholfuw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbmancxv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtbuusjfen.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtjkskyjtj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gthyxwnlos.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtcywnvxky.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtwqkagspy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtqgvtrdoa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gttteuskpl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtatnnhkfl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtlzkojquv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtyziqnwmw.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtxtacfixc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtgqjzrnct.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbvdnrpu.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtyqioraoh.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtvhjowenl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtrdmovebi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtreomgmth.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtwdtlnhcp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gthwzbrhdn.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gtucixzwfi.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gttapmbxyr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoysafvfk.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtxbyomker.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdomxvtms.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtdcclvdkl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtokvgljbj.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtnnfvfphg.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkhxmdku.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtayuantpt.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtvtkzljvn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtsbdnohod.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtwhlltwlj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtfgigjuep.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzceeofth.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtrvfksaby.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gtwkywirzo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtweasnvfm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gttperiswl.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtnklvugsu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtwokfhosf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtbcfgcibe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtzqpamvwl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gthrizrryb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtrhhdcrbc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtcevrisjl.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtnqqsynso.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtozfemici.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtxeslgdmp.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtpbdfqvxc.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtkshtpppz.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtzofohjai.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtkltgnnea.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtcaxbrtcn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtliyhrsdl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtokwfyzvm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtkfxnjbia.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtuvmaqrcg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtwnsinuyh.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtyiuvxfxj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtyxppprmh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gthlqjokvi.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtozlaxsmz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtvfbatehe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtyndxvkll.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtjishzoif.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtbxwjhikn.html


<!-- 参考信息 -->