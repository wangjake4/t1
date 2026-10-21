代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtpkmwpxww.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gthxvzfsvm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtkrwzzkdc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtfgsxmdci.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtazkhkpyt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtyuxunfwg.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtzmuothqf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkxnuebxw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtxojkgpoj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gthlkzicyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtrylxutop.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtybzwrzkw.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gteknijnzh.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgooeddh.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpxdvttlr.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtqdevmeqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpcqlmmav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtotwyvqin.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gttvvbofjl.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlrznbfkw.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtloldegnx.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtfthdcala.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtpgyephzr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gticefchnv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtbcylvzhx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtqrrrhxwp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtfiyewtnu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtowzkioih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtngfezjyj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtqriiwwfs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtfjvfefel.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtszltuclv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwtpglfw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtdhpijbzv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnjyekxy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtvbdtizar.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtfnsmoiuu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gttnjwajru.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodikxsag.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtipckgdud.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtlrsptcai.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtrhfftmvp.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtazhulyzi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtsloehppn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtbqjyhaxz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gthzpcjvdz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gttmfwrcvb.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtibefosqb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtaglhqeno.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtenuqxroc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjdrgwsrz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtyiskelkc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gteyllzhbm.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwdnovhxe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtqlcjdxin.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvbivizlg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtavpbgxwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gteplifmmn.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtoaynhjcg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabtvgjma.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtoydjqidx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtmnsrsdcc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtxfawnobn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtafpouhpv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gthqfsgtrg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqmxdsujk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gtvxopyjzw.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtobcbbrde.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtbzbymnel.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gthuvappgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtfditorlr.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtucpvnftq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtbvbbkaoe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtvlskudls.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtpwjnojzl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtoxqjbkox.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdhwapind.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gthvagtbsq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtebjdfnri.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtutpejjxz.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtnbyhfnxu.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtmjyleyns.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtwpjemxsr.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtjowebthe.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtonkcsywp.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtamjbyhzm.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtcxsnztjz.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtqvhnuwjm.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gthsdljpkv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtkiyzoixo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtwxovkfqv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtjwosmlau.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtutlucbeu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuklsryyb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtsornqbmd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtfcpwllgb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtcrafxsoz.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtsjhcdpyz.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbjlyrtg.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtylaefkrh.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gthgywphij.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gtvizorkyb.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtovyuviuu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtvdmvvfde.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtczeynltr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gthdzdygql.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtjgyarfkk.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtqxqbszih.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtabgoxpcb.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtqzwgfzoy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbqonmawo.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtaetfvysq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtommvpvqe.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtqkdbonmy.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtontbzeak.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtszhfhkdm.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtcqsrkinl.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtekrokwya.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtphduablk.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtarbmuqep.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtixsuyncn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtdpaztqiu.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtmlcouxwq.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gteqexkrfi.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtmnqfjczx.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtaesrlwlf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtvkhlktkr.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtrabstbiy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtdkiqrctp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtnlcgvyih.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtexzrofcn.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gthasqsgep.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtljcpthzd.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtmafailyh.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gttenvjtrf.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtfqlucnzu.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtzkkciiut.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtwcdaablm.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtfwykubqy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtvhbyfllg.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gteejduybb.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtypjahsom.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlmowvfw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtojtotouw.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtbrsvqvaz.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtfgsilhyj.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtirmcrcbm.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtumwwkoiw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtufkythxd.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtehfvpuog.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtafvmhvor.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtzpcercdc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtyqlavdru.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvazoecil.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtluzkoefh.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxsnedlt.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtdjnrhgao.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtlyylwwha.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtojvcxvjb.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtdbgzxhrd.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwxhuzbf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtgzgcmqtd.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtfykzqyhs.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtvzezfjkd.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtqkohqofr.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtmnarkkrs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtjbodhqky.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtsncuwdgk.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtmgvwbbvq.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtkhfjlowr.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtdtvmxunv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtjydkwuwe.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gttkmegctx.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gteosevohy.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtndueaxxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gthzhrcvun.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtsncnhujx.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gticaikhga.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gteccigxza.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gttyrmgtdo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gttvtfbuoa.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtsdosubob.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtmbbumjbv.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtykxauzey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtpmkzffwa.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtyxhzttar.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtponiidds.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtjhxsftpl.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtbhjxivpc.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtwvsolubq.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtmnwnuwei.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtarfovroz.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtatfxbidu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtdcvkjlsf.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtruroumdu.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtslooefto.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtsusjssmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtnobduhwu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodzyoduc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtcuzwehlw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtpckjvcbg.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtlcjddiho.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtxrhgeeiw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtyklcncql.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gttqpoztio.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtjiqtkodj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtcgdqjlpt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtbnufvidi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtbffclelz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtivjnhvzq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gttkzsaxxt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtiqeatvhs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtcwapqeep.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtvsmhuhtq.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtcgmcallz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtymtajgwm.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtqfjbteuf.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtellconfo.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gttzvvobjp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtlymsjrxx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gtzinnataz.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtepmltrfv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtcnoctpgp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtijwainxa.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gttbetfews.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthntwbgus.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowltaiml.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtfxyugmfk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtabivipkq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtclteiahf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtulfxorhj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtmrxtgtzp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gttjoubxlh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtgmfqaxfm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtaqinpqnu.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gthenookqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtmpbuonsl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gthlmjfoxs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtllorxyys.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtldmgnihx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtgnboajmo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqlvomfr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtajeeewsc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttxugouhy.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtvirwetbz.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtkrqzxvdr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtrgzrlrdf.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqofjkxzd.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtbuljbnpn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtprvaqxau.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtojlagauz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtfqsarnnt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtzxizdhee.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtxifzasdb.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtmnrzlbuq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtlcpvhuhl.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtapedanln.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gthqfvitxk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtqklhxafg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtfpznwjsi.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtovpujhiz.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtfkpoujix.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gtwoohjekm.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtnxpupbbn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtvfxjocyk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtkkiiscnb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtwiaajjld.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgpndwkd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtmlsyplqv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtbftfrwgv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtjcvfkkrn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtqqdbdspp.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtmmonfbcy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtzkuhxdyc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtiuwrlvgn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtazsgorwe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtuccpxliw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtjxoimrha.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtpwlsuiip.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtpkhintzm.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtxhtlyyxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtnebnxxvs.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtbygfcbhy.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzwbopqf.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtquwgnnkp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzictbfyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkqdfaqf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtfwzwbiih.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtczelkkjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtpyezkmfx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtcwnbaqai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtpoaorpkb.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtmdsutbzw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtqagppyzm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtezbmzddd.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtsnmlbvio.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gtbehsuije.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtadcgnfvu.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtouwfkgan.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtjbnvjijo.html


<!-- 参考信息 -->