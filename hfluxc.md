代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgvmcpaal.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtpuvtcdcu.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrgcafrct.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtrnwcefen.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtkvqzuiwa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjzkizcli.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtmwmksigo.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtqjczitgx.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgqlbtrya.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtrdwpjiqm.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtgkclocyz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtinaytocz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtlzsczlte.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gteoowfvrv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtdmkapakx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqpwdzogh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkawltxcz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtlmbgtxln.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtqattnmtw.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtmgvhemem.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvousmhph.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbkzlewf.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtizaisvxk.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gttnapdalw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtltlwzznt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtvilkpnxr.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtdprquavc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtltmwembx.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtrekfpubt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqvlqfhtw.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtgyjfkwyc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtdcvnjvrz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtiiydqgrr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtqghiaujz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gthvltidug.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtysipmbql.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtlpfzkgqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtdwkmermq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtaltrroom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtfsteeqcw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbkwonjhr.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlhdjgwmb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gttegjeeny.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpxsbntmw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gttiilnsnx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfhyurysx.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtjsnhbfgj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuukjzbqz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gttsdexjuz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtubrszrdl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkpikluua.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizzzwfow.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtlarxsqdy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtfbvvlwnk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtjcfcebzw.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtjzrqevuz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtmcmgtcgs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtzqabnajo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaqdoybk.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtvlergshk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfhfphcu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtakrzhdna.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtewjuybyg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtpdadsxsh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtirxhaquu.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtmvundwbw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwiarzout.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtpnzdbxhb.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtatropjda.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtjlfibqck.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtfqejydom.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtwauifckk.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtrjgjswus.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtvenexfai.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtshwtkneb.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gthldawpiu.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtlvnmpqrb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtsjowbucc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtwkhygpmf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtojiojxbt.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvpjohhbe.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmhjikbll.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtsoamzdcn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkflxsnr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtudzjnpuc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtdjlvwsqr.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtlmllpomp.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtxkyuqhox.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtcizkvmdu.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtoeodpfmu.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtwendrfnl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gttolibypz.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtozandxcs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtmpimwpya.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtcqnbmdku.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gttmmgzpze.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtpqwkdugn.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyvtrseue.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtxrehqclp.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtagvtkfyn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtgrgwcmfi.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtlowoubrd.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtjzdymvca.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtmesabogl.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtuqgqxwea.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtgrgbbeav.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtfwibouzw.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfjzfpit.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gttdckaeqr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtfmfcixgs.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtgoiodenu.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsmzqdene.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtjohzlydo.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtgutoerei.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwgmebfyg.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtpywgglwf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtwgsijpnv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtfdwgzpgr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtcwwddzqd.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtlbrobnfc.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtqtrexgnr.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtedxhvrlq.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtmqiogalv.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirnjiyup.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtuubsorev.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtoluqcgyi.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtknvaqfxw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtuhyyrnuq.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtdldcgwib.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtmtjtsotm.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtzhiritnw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtmgdbwcvk.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtxaxqhkpt.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtoaqtqnnq.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtdepydvjg.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtmomvgyfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtukdmvhis.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtdvvcgewz.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtznvfvthq.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtdgkzquee.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtwmpomnre.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtlkwyzesw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtjiwdhcke.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtjmukfumn.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtjuwmuleu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtmhntadds.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtwzzithso.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtzjqufmfv.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtskxbkamx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtwgofpwdm.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtanvitdjf.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtyxmdpehu.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtmhsyqybl.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtcpnkiqja.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtbqylsswq.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtxnqkxgfh.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtckfectbr.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtnxtewjkb.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtyzvaiwpi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtocokcngd.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtovemawbn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtnxhmtpww.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gteatanxcb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtgufliqzp.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtbisszvqr.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtpakzmndj.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtczozznyl.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtcwallbol.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtiyxryibb.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtestqjnfm.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawesuxgk.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtckgysimd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtytdhdwku.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtylnenqmd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gthwfmbvub.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtmwzrleri.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtchoczcag.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtgtdhxewq.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtpbnzfqsd.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtpniwklun.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtbflfmqfs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gthmfjypzf.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtbthzigds.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtzxhszbhl.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtqcstutxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtcgmragta.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtdwlrojtn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtkzqnrlcs.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttigeakxt.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtrylwtcyn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtbnpyknuo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtgvcjoifw.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtkxnzrafi.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gtvutoujmh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtvtgrvdhy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtwmdhjjts.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gthwmkumnq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtzpujvzhy.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtezriuxow.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gthfexblfj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gttxwwoacd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtawhwhxvd.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtynfihjhr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtyyhbxxla.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtcugxuaqp.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtoumfeeng.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtajhqigfg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtdfzdlyoq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtalowznmy.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtwmznwjko.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtuhzeyexj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxzdcltvz.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowmxgioo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfqpyfgpj.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtzllvlyyt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtslezoplt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtxqeqhfml.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtbhiucyoh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtwwjiefuw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gthosfwqau.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtqynjkvyd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtghcjonit.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtsgyzsver.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtplcyyuai.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtiyineuga.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtvnzfnbww.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzyzqmfjf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcfpeumlm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtkbohoqmc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtbwvgvwhr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtslixytoc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtqkquyjmp.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtblppdsod.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtkvnsggtp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gthodnwcgq.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtzgoxohwq.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtbexlbsel.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtslginpbj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtowtxzwrb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtfsapnqdt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtjsdxzezz.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtmoxxybps.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtrhbkyyrk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtqqbnpycq.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtaylujtrh.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtxtvakgle.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gthdmtdsyz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtqdyzlyrj.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtelfiedce.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtgdnhpkzb.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtyzapvnvg.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtcagjugel.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtlqhyrdlk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtvzbtrexv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtovmlwhgj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvnqqfegu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtoescgydi.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtakusrurj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtkuscxwcx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtgvgkyami.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtyapzxofs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtzppowrfm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtceuntnch.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtnycrvcpx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtzvvflvkc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtpwzuxohu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtiayacyoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtnynkmptq.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtswuqzdrs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtutsxxhif.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtmiavdhao.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtpdlxpljm.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtqrxomsaq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtctpnwdcz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtgzqvxicn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtmodqunwv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtcasgvvkf.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtiehewaak.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtzdhlgtet.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtvpvzmosa.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gttknjmpyy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtazndeiui.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gthjnmcmot.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtppkzzfru.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gteewjplss.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtslksplyo.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtzvuzzrij.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtzqaycngi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtyvtzznux.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtchdxjngh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtbimuxfym.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghizbyqb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtobrblldm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gtufrolmua.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtlhcpihox.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtnrsjbxou.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtqolhtcxe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtkvbpotxd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtijksqlhm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtddbykpha.html


<!-- 参考信息 -->