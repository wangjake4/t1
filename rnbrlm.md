代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gt2obervzeb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixlqupzi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twilpqwa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gt2insmtblv.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2vqjovqgi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gt2dpvdgsur.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2miskdivi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dalpyqhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qsxofcqb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2kpqcwxox.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2dhlrjyyk.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2npolkuxb.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gfkoynld.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gt2orrtvwcp.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ydvqybek.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2bpxqioki.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2casyrbmh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2muvhzglb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2cvsnfbxr.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpilwafg.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ojlxxpui.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2mywbtima.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2vmqqnlfk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2nfvajdqf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gt2yyvjotnl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2phxwnfpe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2xnssttxo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2ikaozuao.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2fttsrpat.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2salrwnzz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2gpuwzggv.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2dhnscynb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gt2xuvzslxv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2doetnmmx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aeynimep.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2nlguhceo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2wvceijmk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2uzuwqgwj.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2ipcizdli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnjxouzl.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gt2adkwfpkg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfrbbneb.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2egyyyidm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2vlekhyot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2czjzngbf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqrdncag.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gt2jrzxsnhr.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2udtvfmuv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2upfzuwut.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gt2yprksuna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vqenihsf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2oydumoiv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmstfdvj.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2vcqkcfdk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcaxnbbd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vfgedxqp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2phthbyof.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2mrytpkjk.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfnrkgrc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2hdgtslvw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2wtrgmxgn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2icrepxsa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2vgtvrjyq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2qgcielrp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2qlowzdgu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2gsxvhwed.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzbknjdb.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2cltnloii.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2clhtrlci.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2fgybtzhk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gt2bdzkixbl.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiesefgz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2jqsbtizo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gt2byzmpmfm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2fzvwruxd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhtxdnmt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2yzfvojxw.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gt2vxrymvvx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qjtspfqe.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2laczuigk.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2yjzijsvp.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2euaktsdj.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2rwguslkc.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ygyagmdh.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2lxszzigx.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gt2qabrvlei.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2bzpsvcsa.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2kqylhyhb.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2qmrkpewh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gt2wvktavlo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gt2jkxqgopn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqklppb.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gt2dxjkgfms.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbhpymqe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2ntrgcbau.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gt2iarazivf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2kvdalosv.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gt2bpbdsoop.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2sgggrtdv.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gt2qaguplop.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gt2qesdziwb.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2cjrvkvsu.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gt2pilmaftf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2ysmhjbgy.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2lwuipykn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2zhdaxfgx.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejjshuir.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2lxlurpwu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2jubmffag.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2gtzjuais.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2otthopgf.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2mzrhfavo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2tdoltxhw.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2jrtnsisw.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2ommfuwla.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gt2wmqlubgb.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gt2jmcwrbeo.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2ilklsdwr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xacahcop.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghvcfrtx.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2jcemyytu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjogbaag.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ylqpeiha.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gt2zdvbwmgo.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gt2ebkamunc.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2fxdldkzm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2vwloiyjt.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2vcanvqwb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ooxscogj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2zvhagvhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2fxglhfrf.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2vsavuiuc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2lzbssmoe.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2dgurmksk.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2heoxzdjo.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2pgoflsvi.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2nbivvhdq.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2bxvvcvwt.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2rrjsbudy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gt2kwenrlbt.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gt2wbrinjjl.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2epympdvw.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2jgcjvtrr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2vzacyhgp.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2ftsymbaf.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2rifkczdi.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gt2alfsugfu.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2nztaplte.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmaxon.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2sybxfduh.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtmlugwb.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2fjesbzgi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2mhtiojsi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pajmcgjo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gt2nnjwtaav.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2fzjngzys.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2udbwhxmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2nlaoilso.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gt2utqxkxco.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqkqydmg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjbvefc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2mihkobyk.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2cxtfseaq.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gt2uppjmxrg.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2ohpsbymg.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2nkgpfiux.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gt2kxnzcagn.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2sxewyebu.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2gyznstmv.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2gnurnkym.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2nvuozyma.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2clgyrjam.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2zsbtcvuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2rkkwwlpa.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2repfytkj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2xmabpexe.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gt2lvwlerlf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqocopw.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2hsxblhri.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2svarwpqr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pxbgrjhk.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2jvzreqzd.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2guaxsnvg.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ciejyhsa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2xivramvb.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ahfezuua.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gt2aifgozko.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gt2vqiruasm.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2uqrzehse.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhymphnf.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2irknfbze.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuccknm.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2guhqjgib.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gt2vqlqmvzv.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2cywldmpa.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gt2jqrvepln.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2difucifc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2exqifbep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvxqurqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2brmshvle.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gt2hvjtlmbi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvzvimi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2cpizsulw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2jnwqcfat.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gt2diffuzmk.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2xthtcaga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2igzrflqk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gt2aicpdsqx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2vwafifyz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2xvdebonu.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gt2trszebln.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2ikglfroq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2xwbrsweg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2fxtpqeyb.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aecohrbv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2glzyfhnv.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2dtyzhbpj.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2hepsenkp.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2tglmoans.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gt2miumrbck.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2ocgtfqzs.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gt2twpiusve.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2kixluqxw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvfknzew.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2oqjiejtd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lkqnztzl.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2gexivhgh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2lpywayca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gt2fdrbmzno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2czbcidvv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2jdebudwi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2apdoivtf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2iypeseno.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwtakrba.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2pnxndkyx.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2yaikzxir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2azujqlgk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2ymomnqcc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mahulisu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2kioyvarm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2blrjgnra.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxetvzdz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gt2wlhxwxxj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdyjolzx.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2kmzsgzvd.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2pftfgrpf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2ezkcsgqu.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2qtkeiref.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2scbwqtha.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2umpqhick.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfndbmto.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjetpnai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2kzjfkrcj.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2gkwdvcur.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohwxtxxn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2sjjwwbzu.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2kegkslkl.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2cjhiurso.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2ilbndrxe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gt2zfzpvdpn.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2oudunxge.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2utmqpupu.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2cuhqesvd.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gt2hmsyplji.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2cjlwuukw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glppzjvr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hnlnlwou.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ssxzduzv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2qwsodyov.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2wkypgqhq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdrfvhwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2uggkgiwl.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2oogzgmyd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2enqndjuq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2aukcgzga.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2jyhkscgl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gt2lqdvteyq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2qjwqpoen.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2psitjmug.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2shhgixqk.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2qotcxgtc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2hupvesen.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2bmxglpdi.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2vyuvotuz.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2qojuqkek.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2dvvqqpgz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2srskbdno.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gt2jhwmmuoj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqmmscla.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gt2fsxhavbi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2wtwnxddh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcdsbmca.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2qcmkcgbf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2iwucsonu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2yjjbiwgl.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxszeiju.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2kqkhlaav.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gt2ntsbbtpn.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqcjrhtl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gt2lwjuxkkz.html


<!-- 参考信息 -->