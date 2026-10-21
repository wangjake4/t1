代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsgenyefp.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtswwdrirg.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqecapume.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtpskbjnqs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxzvoyxlr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthuysjjwh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtukjtcyvb.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtljtviddj.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjghkoicl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtzvgahdhc.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtwgxpcnoc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtkoacudmz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtrwtazbjx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtvarcycjx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtmqcwucty.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtlntrsagl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gtxrynqnoc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtqmrukzee.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtfevmvgwa.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtbsjoxwzu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gthmnbydmk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtvsphgjaw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtkgldgdxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtsvbfihbw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gticsjscti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcwrqgmj.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtjoghwhxm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtqwwswvha.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtvxewajxr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtifznyedr.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtyyingpwi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtzgnagaip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtajbjweah.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtuxhalcmf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtqgptesgt.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnwoxhatz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivzxanks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtuhtmjeno.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtpweuzfkn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjzkrfdva.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdszehyyr.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtswizsgah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtuuoirzmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtibwxpoqf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtedmtygwd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtiovtmtsb.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gttcwinxzn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gttwjsvhza.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtfeyfguxs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvouyfvg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtrplsntrc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtjuidmuig.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtulwlrutw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtohptwkrn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtnahbmjlg.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtbphdlzzq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtqebtiqvi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtyuuaahns.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtpfewsnsq.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtbqcbunmf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtdjcydovd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtmfywrfjo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtvlzghrre.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtxfeswfub.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtefjlgnop.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtxfbnpohz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkrgekynf.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsgxrykd.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtkewgvakt.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtnsekfexr.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtetcsbszm.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtmkmzkbgf.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtwlocuclu.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtwjzcxhny.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkupsssh.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtxcyubagt.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtorusjnsu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtiolfidrs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwaakgif.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtwojmfamy.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtohswupqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtolzykupp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtecsfhgct.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtbtnsjaml.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtmybzrhur.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtybpznifb.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtyhwoeqhb.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtinmfoyuh.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtxsvxzddj.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtebandpod.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gteqorgfkb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gttngjgypu.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtlbavpccl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtxsggricb.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtsnodcwmt.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuiuutuc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtiyuhvqwb.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtndsyjfox.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtgwrzgfmc.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtwalgxrzq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtoqltaslz.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtpwlpqjqg.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gthmsqtjbs.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtejmynytk.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtojtklegu.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtfpbaxwqz.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtrtsguwvc.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtkjmnwmgw.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtplwjwggw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtjqdbnafw.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtyatvoala.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtvvkrsrjy.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtkgkxklef.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtluydaqar.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtthfazbdq.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtgtljogxm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtojaikilo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtwuznvujm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtikqrmshz.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtjblkzmyz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtwyzmkhxe.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtmunsjjqe.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtbtmtxqjh.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtmjpxymiu.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtwglhiqod.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtdubgyiol.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtynpexicj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtgqsiehtq.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtcowegfkj.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtzkjojdzp.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtxusdjzux.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtnxixcpgc.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtdiomkple.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtytozgtkc.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtvawpptfq.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtojpvaqlp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtlxpzcjjo.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtepmgnttn.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gttjghpyxt.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtoxjtqmux.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtpgjtcsxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtnmxurxyx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtyeiudysx.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtpkcsvqpd.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtoqqdawzd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtjiblqomd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtvbfxexhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtblspqwvb.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtivkqatmu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtmhafcmea.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtinglxrek.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtcypuaxfa.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtzdxmiqad.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtystmcmfp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtapwjoego.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtnrhpzsyq.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtxciwrvdr.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlclcpmuc.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtgvgwkpbg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtzbbeflto.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtorwkkqgo.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtwxnhetmn.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtmtxqexol.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gteeegmgiy.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtkyjencjh.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtlezqnsbz.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtvtzkazuj.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gttyggejsl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtlkkjmszb.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtekeqxwvg.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtzlmnxchs.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvbumbmvf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtuupjubhu.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzavlhkw.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtucsarxko.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtcqdvufaw.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtknyrauvw.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtuuljhrbg.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtaijpfumz.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtwlehllnp.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtpwwmxbtf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtocgryuuc.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtkfyrship.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gthlworant.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtozticaux.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtpgigipmq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtxhabcbdi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtnirhpmnv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtusmmfkdx.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gticptegpq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtjrgufwjg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtaacgwcdb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszswnuoe.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtwxgdkzto.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtwhyvvzsw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gthjltlxug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gturrnbqyo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtpwthouih.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtnlxzfuyp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtjruhwuoa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gthdxklapq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtvtfkhxup.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gtncqnxcfy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtzaqyjkdr.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtceyezqpw.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwjhmekis.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtavcxzvzk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtkjlcmdfz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtxecqzisv.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtwbnyjnzo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtvbypgxzk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtovijtqed.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtgobaoyyv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdsxzjkmf.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtgnzqcrca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtetothugu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gthhpphidy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtetqbrcho.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtlmiqeaev.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtbgoovglw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtyxmrnpqw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbzbotdo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtrujbgpsz.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxeoygbc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtmxsdyzqa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtpgqydjzj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkidtnlgg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtwthkubvo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtrubsbsph.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtuebxsmkh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtybeuwmtp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtvnodeikt.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gteferechu.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gttqiyekxw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gthofoqifc.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtfjhqykne.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtoihgrffv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpobavvgs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtkuxqwhex.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvjyuovr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtthhxmwvy.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtomonkmgb.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gttxjsavun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtnorjqxzp.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtpabylcfi.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtacrxithx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtvvaadrgu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtedwfeawc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtgdaczyjw.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtekjyybak.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtewbxpwet.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtfedufpuv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyvwyprc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjjesmau.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtgerfrkii.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtphbgcwqu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gthdrthdsc.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtaxoxgppv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtywhbrzrl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtovruqdil.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtppjqqlhw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtfnwvcoxj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtxrsedzqy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtbniiowvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtewpsxbfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtzfacqqdq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtjjrjlyii.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtwefhapke.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gthdotbsme.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtxulzlfbr.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gteewyymcs.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gthhqekoak.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtjewaxgkg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcpqjaal.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtjydyjpuc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtslfkvzhb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtaoknyylb.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtwaerktod.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gthsyutrkr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtpeluxbem.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtaozbqfpg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtosrwutfp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtzlcyqkml.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtrrphczsx.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtubqxtqdr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtiknytbld.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtmjvjtyts.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtoekchgqr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtvyhonvqe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtotfnsmue.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtphlgmpue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmctezink.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtfinytryb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtpvqnfang.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtjdzpdkgi.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtzgzztbpo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtagdmqtiy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtbwrdqxab.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtnmvsbvbx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtjhqsgnyh.html


<!-- 参考信息 -->