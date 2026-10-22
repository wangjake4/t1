代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtliojsyme.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtuziapcko.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcupqobjb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtbdfmwuwo.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtbfaypczq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtvznburbw.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtgtfecegh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyjnblxtg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzrprqbas.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtzevhabef.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtegmhbpga.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttorrkmkq.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gttwunhrcj.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtzkgjacpw.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtbsxmrjtl.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtrkjqecib.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthgsnwfcj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtoehvkgzv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtgfaztywk.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjfzeipvm.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvlsxcsnt.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gthlcqdfhf.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtyvjxvnns.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtsnvrocig.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtqbnrsszr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtmhlnlhpq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtohgifjmn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtkykhpjxu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtnhpvncff.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtrjtunqdk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtthqlhdgq.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtcqbjwlze.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtklmngdec.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvxziipk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtndzeuste.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtexmyxuag.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtuzaobwsz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtvfdyfpcr.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtseocnwgu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtzownrcgh.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gthaenibas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtticxmgig.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtdglhvxbf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswkzowje.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtkusnlyen.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtklmobevb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtispsbium.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhkdvijl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtbqpongrs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtkzngsvzh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxqqmywfy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtljpdvipr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtofkiwnka.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwjetdxva.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtckfnamyj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwqbvajwx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtuuyrxfif.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdjizuawr.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtglwgkrde.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtufqkwder.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gteuumrefl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtvhsmdnmd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcgxykpuk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtoazniyca.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtrvvobcxg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgyeksyjr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtadczckbq.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtqouuadpl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtsidpwpby.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtntyqrlne.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtnpwcbdnn.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gttpknyemq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtdcukroup.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjmrwapm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtejxfajxe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtjthwlwby.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtduxrjacz.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtptoxmkbc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtazxbemyp.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gttoghkech.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtscaocpmf.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjtspeyle.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefzwhstq.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtatrwwlvs.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtejhbdaln.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtrdcdwacz.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtcnfecngl.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtpqzowpke.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtqvqpefvo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtccpxclxq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtsstreaqt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtkkbelnld.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtypywlgyt.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtbbvfavds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtkanksjrv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtdighjjbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrhxpptah.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gthuezkeny.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtnoqiimeg.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtyhxfjakj.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtgjdmgcgs.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtzcvutsfj.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtuxnjhums.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtbtlahhfy.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtwdqtbemr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtrkyzxadp.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gthwphskvr.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtkkkayhiv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtovqtjvdc.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmxhuooz.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtfqprfqwa.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtdwdplzgq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtcybtonqz.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtduufznqb.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtjcxkrgfm.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtztynvdbd.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtwqmmfnzf.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtrufwqlia.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtjoccepnn.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnbwmxvzo.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuqhkbuv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtxnmsqlzf.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtuusxagre.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtbimwjjpv.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtdqzuuzsk.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gthfkbtswq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnndzxisz.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtxlcegxfd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtwhtaiewj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtwnegjlww.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtyunwngly.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtfoabrdqh.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtfcogmwok.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtmuziffts.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtypiyicrc.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gthqiouibb.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtrcracjze.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtbytgkddb.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtdogurvdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtwpqjzpue.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtlwypvuik.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtlzxvvojq.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtuzfpijbf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtfyuiwhvu.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdvlebrm.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtipgutogl.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtviyvbqqa.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtkwdwbvud.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtsglidmra.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtfxykqjzt.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gttxrsftbp.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtumpjrwgi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtgllhmzdw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtcmeucegn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gttocyelxb.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtbxnkejum.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtbetijiqb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtowpthtvs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtzooewjfl.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtaastjbff.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtxqqkrqhk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtrcjbwxrm.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtluyooumx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtkqvledlv.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtxlgmdkcg.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtoklgwauj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtzpnhscvl.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtvkvyppwb.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtceqopaqu.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxsuylsy.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gthukkdcwf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtgmbykjdq.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtifzpwwhv.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gteoyqnrww.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gttlfrqbki.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtrvvssdur.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtkdutgbqf.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtsfyhabxw.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtxcwcttvz.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtxutpyola.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtpvwvgiwk.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtjushpclj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtosuwxrae.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrebsljtt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtxfcpmdor.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtfsrumplm.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtpvvkjlnx.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtbgmngfrm.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gttcziffcn.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtsjgwzosl.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtjxpochqa.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtdiatvmyd.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtidnmtluo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtnsiilncw.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gtczrggbyx.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtffmmpxaz.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtmnqkyino.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtencvunmj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gttmxrfkuf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtvopdhqpy.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtmnaeccgc.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvfpvuuc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtwkowfept.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtsbultakc.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtzizwaxyd.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtrrvsaerw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtooidsnwx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtjuxvvbzg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtamfnxshe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtyupqpszq.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtjygxsrja.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtrvaghqyg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtxlgeubps.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtkpaxlezm.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtviyzbzed.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtgiwslrts.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtikgujeqk.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gthfgclfef.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtathjuzww.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtvxnqfhlc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtifpnkhpg.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtsfvdwqse.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtpvgoighc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwkfydnmm.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtvuuevttd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxvbucic.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtapsiaecf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtmmfqygbe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtmeglwugs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtwxqazzco.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdcnehdgx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gttmvtstpx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtnphbjdbg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gttkpxojas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtrqgvxooa.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtqfaashpd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqzhbaep.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gttmjcuawd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtytlsaifr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtrckupkqb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtgzzesxsf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtydymidps.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtrngolyno.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtwilaxjzb.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtdwzroibr.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtconjkumk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtzulqbttq.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtjayoawwu.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtwcjggiih.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtanurxsow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtdhqotcol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtcqbrohlz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtxglcxmvz.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtqstsehil.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtojchkdyq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtcxluxsms.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtkbmcbfxn.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtcvfprlql.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtxklwqafx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtthedmhuk.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtlighkjnt.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtmxtlmprd.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtfalkqpsh.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtcqoviimi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtuedwrjah.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtfximyxfr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtwmxswkag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gtyjwcmins.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtnqvwrvyw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtossnixpv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtygbmuqwu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtchtsvrdv.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtnfxwcplr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtcplzovia.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtsjfilgxx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtfmayojic.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtilgsbmrd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoecxjmt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtkohplvvx.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtoxazdhjw.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtznyinmgd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtwgsliyed.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtffovzzar.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtljgxynmw.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gttnqtffvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtjjglnwet.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtbjlrmdnn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelblecsa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqzdotrt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtxnheucmc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtotzmxbtj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtlircqfvn.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtvwmekjhz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtjzjwbggq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtqxfksdmd.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtlygakpem.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtstslqkkt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtnjtldjhf.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtazryqyib.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtvqdpajir.html


<!-- 参考信息 -->