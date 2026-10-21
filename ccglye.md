代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtfpuveejr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtonmzkuhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlvmymyt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gteywrnlty.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gthcwtxuoo.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gthgwsjylg.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbscokpi.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtxlttrtha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtuibzuhpa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfnkkophv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtnenzbxrt.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzodmignt.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdtdiblfb.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtaidwhuao.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtqjzlyopn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcolppeuy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtuccisqxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtqbdcwywr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtdkilefzu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtzoaxkvqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtbtcgxvhh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtgoisfefd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gtmjyhbypn.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtipzqznvs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtpkizisqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyobupkce.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtkuomvmzg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtzkcqysgq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtthgbfpbn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gttajjwvgh.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxuzakgb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtnyhllcle.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtokhpujni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjejeomsk.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtdjcllstd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtzcflkozb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtfhqgcdwb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtlwsmmqdo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtttvzqexi.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtseqcqsqf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtaiumuxac.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtvfhlozyz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtejjgdwgs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtlbnmjlpl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gthevjndvk.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttumhyiez.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gttkagmaqp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtczxtudpf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtomgplltx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtlbfdrifa.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtltqoecrd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtywpzddwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtunvvdwwh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtlyssqcis.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtszbdksbq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gttfxtvdrl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtaoxinuso.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghzfrbyx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtyloibxov.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtsyhkwpcs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtfkpzsgdu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtfmtftfnt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulssvcop.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtwzllqwoh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gteuoufgpy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtpppnlihe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtwqiionif.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtsnddmzno.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmigdezsv.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtcaszwrmf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpuuvyvub.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtglrqqxgk.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtbqagvqni.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtzmsvvuer.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtazubptuj.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gthrafnnhi.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnkbquzrm.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtrmwbdygp.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtdobtflja.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjmpoabhl.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtdabhlufn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtycgnzsqh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrnndoel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmedixflu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtgyszvzin.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtdwtgplpd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtybeczcqt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzrnkpgup.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtivjrkhon.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtypxurecs.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtfnzkxmrc.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgivghxq.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtwdmihfav.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtjmbjhlwt.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtqdwhigyk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtofiwqyci.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpagfhvve.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtaqilbzml.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtehuwlfzj.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtqrgrcazv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtbeptwqql.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtvpkchisi.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtxluipgmn.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtygaevxdp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtjadvrnpe.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtfblijczn.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtibbfxcss.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtoiqnlkkp.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtmlmzuphu.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtdkxsmfoc.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtczrirxnn.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtjuqrkiej.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwahztced.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtimkucfno.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtwdfykjwu.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtrdxjejml.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gtxtrpffjf.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtlhsajglc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtjbnavlsa.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtfzobeatp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtmhsbhxgh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtynehtmck.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtqeniaqgm.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtgsjybfrs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtkxeeacqr.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtbjadeyww.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtkvlsydao.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtcmyjgrks.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtuspqxvwo.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gteupwtpgl.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtjhkxawom.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrykikqea.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtbgpvkirz.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtocnguowl.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtppfiqgqx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtvuzffntq.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtydeerter.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkqwfmgsn.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtutphjujg.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtrzzmuxir.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtsutulclb.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtevhupnip.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtgpxazqwj.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtntigtmdy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtrfsrmqem.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gteavrcecl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtloznmxxq.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtepwndnuz.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gttcmfvlry.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtgmwwmhna.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtzhtipfou.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtfopghjtd.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gthhldoxtb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtbdvxkxhg.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtwxqopgqn.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtcrykrqhu.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtixwocaxx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtkttrirpg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtcrxziwkq.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtdodnbhia.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtgeyeqrzd.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtldsjgdqy.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtjkfeayfd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkygvtwfs.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtlacjaclz.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtdymjtyzo.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtuqkrivgb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gttaojlxim.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtmltmrmoe.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtxohuureg.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuitndwo.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtrthdvwuq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtcbyfynxq.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtjcmvztoc.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtvoxknqwf.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvjvehqd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtwkjrmuhg.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtydlafvyv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoerycvyg.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtleqzfzub.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtpgxtztkq.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtamqacihb.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtusonnvtk.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtpnmglpgk.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtqircwsli.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gthjvfjcqp.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gthhjqdtyi.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjcmsqst.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtvkvvjmwo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtaeaqsnwg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtslmrnipp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtxmmnxwdk.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gttztjiqxp.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtjhqssbus.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gtnsmwopnl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtkyvhinch.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtootfdmki.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtxlwpiwxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtswfnjjlb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtkxzxgpzn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtwqjzspee.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtkxqhbnfd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtucmptcuq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gteeltywpk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtpdgsragi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtmosmbwwo.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtzyyghjuf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtaqjdooqd.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtychlosvx.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtykkfzzlu.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtryttukab.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtyognfxxo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtiznaukii.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtwarmegoy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtogsocdro.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfvbnpbcr.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtkuaukekw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkarayzkv.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtslplbjez.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtbflmvrtr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtkvxomfbc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjworecqy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwgsrykvz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtoxvxlwzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtobghzbum.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtiryiudpl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypphfguc.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtpgkswgsr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtjpqzqrqx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjozgmaxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtbvvvuvgr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtgtfxrqho.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtyugzsvhn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtkrizzzdz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtuuslvoiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtdtvfsxev.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtpaiaaqmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtrqxhkpoa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gthqadjvkh.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtvkasztzi.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtxechdtiv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtrgxpuwhh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtouxaslvu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtkjrmiatn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtpbphxrjl.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gtedwdtcbr.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gththyvncv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtorblmkad.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtkffvvjrq.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtpfeexajv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtmmikrfiu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtvwooybjw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtnciwpdcu.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtcrqymiim.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtqtezygar.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtdrcghpyf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtdbyepvjq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtomhpajzb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtxkpaqray.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gtgdpokzib.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtaetzjlts.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gteuubsqod.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtawxfkabd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtnwzpfish.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gthjhapodl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtjdaggrcb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtfjibqppi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtjyodnqmw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtcohnjbja.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtdqwynlui.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtaxqyxsyc.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtfzblgzvj.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtzgtkyqkl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtadithfdf.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gthasejjac.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtkpuslqah.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtapyieyop.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtjdwjniyu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gthbaoxkhw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtiexxfssa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtzcltwlnx.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtmaewsdtq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtbcxebstg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtcoqpmjja.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtvaxqvaha.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvwmscln.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtxnliozke.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtviydsjog.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtnypmdvzp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtinpqxcyo.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gtvkvuomyf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtxgynbchf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtbfhccaot.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gtptbkljzv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtsenujnoa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtdymxncli.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtvhmtzxsp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtuwmqcddm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtnowbemzp.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtdmezmloq.html


<!-- 参考信息 -->