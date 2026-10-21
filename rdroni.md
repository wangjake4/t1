代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtytjviwdw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzefiwjab.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtnquvijmm.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtospewxmb.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzsfdvzzc.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtlkkgqyur.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtstjwsmar.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtujjoifli.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtytfeoxwj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtjvlahzlv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gttdlftmzn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtterfhwbr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtslogxdze.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtbbntcmjy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtfceclcwr.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gttrqymxle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtzojmbbap.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gtgagpgdyk.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtpmlgslyo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtdhdalwvb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtfoqlisaf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtirasossb.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtvfjchlut.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtkwaoeqfe.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gttnlezevv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtplipeopo.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtobfpwtgc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtcmzgtpcu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqkuihty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gthhjwzbqv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtrvydrssn.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtrtraql.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtwfzqjjfo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtgphanxlf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttzqecvzx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtvarhqepd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtuefqwndp.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxwwhyxtg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtfkojodxd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttmhiwuft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbzsyaxla.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtjmxpgjvz.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtzxosymov.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtqvfbkbpz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtljyrjfzu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtrfgjzeoq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttfspnnro.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtvtzvwfkx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtvembzlmq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtznvajikc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gthyjrrvqp.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtgosqjxzd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtkatchfwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadvbnmvv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gthusayymd.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtobqnucnb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtfyvvdart.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtdcvkqncp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtmyhikmpp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtmxektxfq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdxlfgfbw.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtfrinpznu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtobazcjfh.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtadvogubr.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtejtnicpw.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtofoatwcp.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gthbqswoza.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtmnuzqqsh.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtvjoxljgm.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtifamdusv.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtxvvgwzhx.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtazvsoncb.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtdqdajmbf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gteikkoefc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxogoxlar.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtqvrpjtql.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtptggdoto.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtnglqgiqe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gthjysmivj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrhqanluc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjhcthuiv.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gtperfhvay.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtdivnpvmf.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtnbbszsdp.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtruosjiuo.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsakfjrz.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtbbsmhhqy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtjnotwkts.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtqueqaugl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtfuxpkzil.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtbcpynojd.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdioxfygc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtprcpwxxm.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gttfojqpfz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtlihylrqs.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrmxgfla.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtleulxlof.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstkusmhz.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtokxdcumr.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtavgkfhnx.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtjeulblyt.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtlxyudkbo.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtuwxwgreh.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtaqprdubs.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowfiamec.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtcxfivfwl.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtnkgoktea.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtpbxqhytf.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtadgdzmmg.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtcncauzou.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtueavtjsj.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gteheaguka.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtdxgvzwqc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gteddioxpc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtmjioixoa.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtafbxvgck.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdgulyjp.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gttokueyrj.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdccljudn.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtcmlzdgvq.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtzafubald.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtsctltlzp.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtpxgsxjap.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtabwvcvfi.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtzscdhsdk.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtysxefwgk.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gthjwmgfpl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtkjtxotny.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gttkqzcfdc.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtithpinuh.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtwtbtilev.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtzaroteto.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtiprfrukv.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtebrmruno.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbibjhpyl.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtqoinsxsi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtuuxyxlnz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtdjphmzgl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtweoqbzmj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtmagbbczd.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtfefrzhup.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtaxsoesdg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtlzqwsxnn.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwxywzrds.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtdeomfpza.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtnkaelsjj.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtkjbkfhtv.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtrirgiarw.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtlsjkrrwl.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtcjhvkyed.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtvbttcsqj.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtnznvrwjt.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtbumeisqt.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtxiarqghn.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtaptmrktz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtafemzygd.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtuourzcul.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtokxqthzo.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtgkzmhspc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwauiywyr.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtzrtvvqrv.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtnveuhxdo.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtewjimrqd.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtutnrezhu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtafnforkv.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtujqkmwkf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjbamihs.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtjhrdjwot.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtvvmxicjm.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtzpwiinwq.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtwzgipteu.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtrlpyabgp.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtbuuvbdlw.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtofbtxvmt.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtxnrqqkjn.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtvsnkdwra.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtiopmlasu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtrygcgzuf.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtublydcsj.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtaxmqutbj.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtfuokztqc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtquniehor.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtyjejdsyi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtecyrplwf.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtjlsxglwx.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gttljdzqrh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtbovxgtsb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtlelztteh.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtxxemotkk.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtlvbzwljm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtnwtivxmc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtlexrdxlb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtcircuctl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtreqjqjmy.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gttnttggmp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtcwxnzwbu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtfhjebayb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtdguuhdea.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gttzrkypyr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtnjptspyx.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtrrfwaquy.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtjyzsiffw.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtsdmfghnv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtuufukjsf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtmpzlzrrd.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtehjxqeim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtwkbfcrjk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtokcvnsiz.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtejvzgtem.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtopertcof.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtcmxcoemy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtumatjwmk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtizsujwuv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtbsmusvhd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gttculbmso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gttkmwkrqe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gthauvqzic.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtnzwqudxr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtjohbbnwy.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtwjipvedw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtaiyunpnk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gthvvquhes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtfkindwgk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtkvjmmhvx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gthiyatznq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjxdlmvj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtpzuqwuab.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtpqocomtx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtccgphavc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtafdeeywc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtwrokgonz.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtjfzxnxip.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtpypzotht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttajljrnr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtbtwsgibd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gttsfjvwjo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtqvhnthsf.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtyyzshvae.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtrqejimpv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtltjdtlhz.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtcxxxvzpl.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtjnqozplz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtqofaucev.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtnfroibtk.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtliocrqsu.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gtuiiblxfd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtanetnovd.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtxfgcaknh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtuzblinby.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmmwikfxt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtqizrkzmq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gtucjirion.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtowkvhelm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtdpgvipuv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtehzoefpm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqvgebsk.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdohwcark.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtbmjspevg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtbyjttanb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtzwwediyn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtavmfpnlz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtfwnekbmp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtdilhijij.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gthdmkfblb.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfdgarjp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtkoxdhzig.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtowhzckud.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtaewchyqr.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtqhfjlgvv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtajidvljl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtxtmnnjlp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtxtukaaob.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtagmxgknu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtnddkmgxw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gthdkdrlfl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtexyqxrzf.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtkvybqnyv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtyakyvnto.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtfvjxmuuz.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtvxjqdpfs.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatcyptpv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtfhocgkgq.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtrmpvstut.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtpyzvrvdc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtizxcuaov.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gttggfqfrp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtbxmhxbmg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtugiavael.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtnzgfjtju.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtaervhoij.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gttucnlfeh.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtcnhhrhqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtlificsvn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtziitoxft.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtneupcckk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtlceuawcu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaptbkkjf.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtzlgfylmp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtookxzjhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtnaepppap.html


<!-- 参考信息 -->