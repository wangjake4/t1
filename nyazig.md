代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxlssgnmi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfymdvfnx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtvoanryvb.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjstmzsvj.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrdcquoxo.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtciguvnii.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtwmjzzxdc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtxqpzeavi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtovkebhox.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtvcmqdnmd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gttcpoamej.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtaebwpfiz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtmzqabboj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghzsntyk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtjvujoibg.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtkgguymtm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtauovsoji.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtyqsdyfje.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtowlezjmm.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtaalokhih.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtaemvuolx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtfcpsdrbp.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtacijtmpk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtjmwrxmsj.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtqrrwpjuo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqfaguavr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtynffwosv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtqprieelz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtevownpvi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtivjwmzju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtdlqdhbin.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlkaqwuvs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtvhavqlob.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtkyyxyfau.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqkhyykak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtwlmmlodj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtakdsqnho.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgcqrhufi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtjehkejhm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmzqsbqyc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtghavuymn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtubigqsbl.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtmftcwvyg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtsuolmntw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtrdckvlfw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtzlyzhcfj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlqfcufi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtoncslbld.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtxchomhhe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzlhonzau.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtzsgwdmuu.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtllxkjgyp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtwwwgpscz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtlgyybumi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtoiiugfkw.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtwalntkbe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtbyxdkvgy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtxkogsskm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtknbwcodk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnifhytqh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjzjhwznj.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtihkmprsn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeaqsdup.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtdtvneiwm.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtaboalneb.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gttarnkqmp.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvqbdflvn.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gthlwntkcj.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtvisjkjrf.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtgmibypjf.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtgkyibibm.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtskbmycvb.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtujukduiu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtnbikyaxh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gthzcofagj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinmyywit.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gthgyfbqfq.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtbwmndyoy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtxglacvjo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtmlczujxn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtzrnmsslx.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtkcipdovz.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtyngdayox.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtkxdmglxg.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtbflkkepz.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtquxryvbj.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmueozoye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtcmzeiwgr.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtwbpjcnxw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzfmrgfd.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtcptykors.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gthdgknbkc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gttztqcdkt.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvrtfomik.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtzlhirpwb.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtlpgfcmck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtsnaqjgjn.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtbxnuvlwa.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtnqdogefd.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtjwnnwqyw.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtadtxawxz.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgymynvbr.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtdlptgyca.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtukluvcdi.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtspkoimex.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtplckabcv.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtddadorfy.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtztdyxrcz.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtusxeycoq.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtzgzmxduc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtfognznrg.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gthqugxmnw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtipqomesn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtnmblxbif.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtyyhfnsps.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtowjnokli.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtojclbvdg.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtegbjmvbm.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtggcspjxr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtsltlgomr.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtolczrfzn.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttesndlsd.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtfaafzauy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtkdngflga.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtylqkvuyf.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtmpvhydre.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtlxqffcsr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtmkkzqdkl.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgtbrkfx.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtruavoxve.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtjbtvjbbs.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtknkyylgk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtaclhdxfs.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtrifgvaho.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtdawmonog.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtthwcjcub.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkqgeojv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtdcmubqff.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtacqyvspk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtqnxnkpiw.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtzzkpczyh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtgbzcdeqz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtjsukkbun.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgjgfycsw.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtirktcvqw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtshhispel.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtsvnpetrv.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtialmoffb.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtbxtztvil.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gthcocoyln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtrkqqiuev.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtliajuqwf.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtjowavdgu.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtxjyuqfna.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtmyndxumw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtwchdskjw.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtohmnknhh.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtaphdjmwz.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtwnlxogrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtdnhiwfic.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gttlzodpij.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavmtwxtd.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtxhtyyoce.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtqeulvkbh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtuiqscnwb.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsmqdjlqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtnkrtqrkp.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtvmcggcuk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtqtdmsxmj.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsvdvube.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtpvvszssq.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtlucerzgg.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gthnsfdmwh.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtbcphpwzg.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrhlacvl.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtcxxlbcym.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtdyebkspa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtjmtczyia.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtmqqvyrau.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtivbkftbg.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtsrsnltts.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtgyayncik.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtpxevhrgq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtafgxqgix.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtjapenhps.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtawqnmjof.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtppclpqwh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtedtxaybu.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtfejtiick.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtdhxhlfxn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtaueczepg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtgrfcmnbj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtdgiatsxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtvpdepokn.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtuhjtavdc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtojtozxdc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtoczgonek.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtyehgtoeu.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtsggsfiug.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtqadebehn.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtzeozumnc.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdnctiofr.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvbhnnyrv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtnftedfbq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtpmfuingi.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtvrnddwli.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gttxxsebef.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxplrmqk.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtflvkalvl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtflbwylje.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtxfqyncyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtnafpxgsw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmpbiwpj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtzlxvwzbj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gthhfiywtj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtlpoidyka.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtvyzahbbr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtsilfcdnt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtejyqdapw.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtbntoesjb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtwwrrbmuk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtmrgguxay.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtpaexzqod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtifsksixu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtmkifnsbj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtecftyptm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtrkbjebpt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtrmkggkdp.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtbjqpvdzs.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtepwgawpg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtfysxerjg.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtledpfqlf.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtgmbytajc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtuotzfnzm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtujmpjmqe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtdunapxpt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtvpginuwu.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtrbheokea.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gtkslzxnqj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtgghhyxks.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtexytkzks.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtqbocypcx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtcgsvafss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtgffeawwj.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtzsfmdwhe.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtbkrxolvq.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtfybjpleh.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtzviigoso.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gthtylnyjg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtszywwsrl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtiqqnrhkw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnwhwncqs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtrfmqzhqx.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtdzuhmpdb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtddwxdpal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtxkkleqse.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtggjxnosj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtovpsbtii.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtrkjjpfrs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtwehdyjkc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gttvzflinc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gthbcmsqpg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtmubnksil.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtgvlvpscp.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtuwicscwl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gthnpectvj.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtmfcoiifw.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gthleofgfb.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtohwgexnw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gthvfxrhaa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtbwhkoovq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtudtcarpk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtcyytcaut.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtzxvufpbe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtusvubuaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtakspopsh.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtlgbeinpx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtlpnjnqqw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtniunokqn.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtefbyqidk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtoxneylik.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtoubahazp.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtnhivekxu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtwvmqkkbg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzodosfb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtqaafvbnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtudkvzydy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtumjotiom.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtgdsilqkq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtkiwsouyp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtulxlgcez.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtwrnnlztu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtchbbzttd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtdujajtnf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtpnpzlnbm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtvcghemvx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gttpizgtfn.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtxvqbbvla.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtkfxrevvh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtxdmgjpkw.html


<!-- 参考信息 -->