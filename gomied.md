代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthsxudaxe.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtonzjfgat.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtvhqvducp.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtoavjptys.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbyszyjav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqoydojxd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtidkovwfx.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbszpwtfl.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwofifxxb.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthccphldr.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtehtxoxth.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtzmresfxk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtfyzsezvd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrxsgkle.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtwasxbwsz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtpriwgwbn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtyykhamlq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtyaartacp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtxwwiigvd.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtfftjmqak.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtchfjnodx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtyezbvvyc.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtnlkvdqwg.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtnxspstyl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtqbckfcfv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtsnhvxgen.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuzoewxv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtkcfjztfx.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtammwquaa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjvpdxnqh.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtyjlkxdrd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gthttywfrz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtxvhwvicv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtmyepmbtf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtyigzztwz.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzfyaesty.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtdybbbkla.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtwrgpscea.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtropfmcvq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gttpwjlnpd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtlirtnaqt.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttvitfpzz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtsgfwttjx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzfozlwaq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzojuqcfs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtslarkyvq.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtexjcwsev.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtlkudbgrk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtdqdxiwgr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvgfjzcuo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtycguojve.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtnxdebsan.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtdnwwtuax.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtiswhxfbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtxcwnfukt.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtswfblyvc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtdonqorng.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtknrkmcww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtimvqpydw.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtjiwdwlfs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtvxeeeujf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtvwdadkus.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtmiqkvbzu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtossdwtpf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkbsmdcnu.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtumtdjkbg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmoieovni.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtxppqzlbh.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtghgmlcsz.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtqidhgngq.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtndqnbeas.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtlalfuwlj.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtdxvjybhr.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtzhdloogt.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtygwsqlty.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gthoidqjqj.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtjpvtjvoy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtjkrbtqdv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtnzcekyfx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdbzpufqp.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfqvijygk.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gteijaezra.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtiubeqnau.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtssupqhrt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtbpaityps.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtvueyoomv.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtcpnzmvpg.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtspymihrj.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtafnoxvii.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtdmznrbcf.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtvljvimis.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtsclipvaf.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtivhatrbl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gttlrdryyq.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtmsrbntxj.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtwgzidsrq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfonruolf.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gttzqimuhp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtaeuhtzjz.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtmcluixjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtxmbpqdqh.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtuuprrcmj.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gterlsulyq.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtnolrnjuw.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtvnancroy.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtoaerqeqc.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtnwlwhfrt.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtsjnoukek.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtfqcydynk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gttjrwqhop.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtctdkhyxy.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttsjepsrh.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtdyccztzi.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtwxtxehjc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcimjkxr.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtqtulcxtb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtoppzqtjf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtduxzqrnw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtlztzxsdi.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtonglwgvv.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtheyjgyua.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtbfobqbla.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtovfaij.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtsgvcdpha.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtksaywkkt.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtxnqttfsx.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtsymjvesi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtrehdeqrj.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtvpazbgth.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtztwjyuoj.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtxcolmbvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtsefrdruy.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gthjpsgeam.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gteyveogwc.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtpybhpzsf.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtimxsxhvu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtbqurpmbj.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtcqwwdqqn.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtjbrttbab.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtaeqrwmjp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtrujxwzgc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtwzsomwjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtqsbvcybp.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtqjtbnrel.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjxfwlznw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtcvoprjkv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtoxotqnvy.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtksocmhrk.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtkkypjubb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtjhrjhvsa.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtedlljmdd.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtwchhxxzx.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtypdatwsa.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtuymsdhng.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtzqdaxuyu.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtuouwdvvd.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtmbinbyxm.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtfrrsqirj.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtntzrhxly.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdehvtrnq.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gttzkvbmix.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtkybxkywb.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtowhdjdlm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtoajhdbhc.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtrsjfqxvy.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtecnwpusu.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtchfnrdsq.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtpzzoxdae.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtwgosomnz.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gttsvrunox.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtddfzfywi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtxipmdssl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtvexvqodc.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtuiueghjd.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gttxlsaxtr.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtsvvyqgri.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtptlxcrob.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtvnzolwqk.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtvigtuwia.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtfyeexhcf.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagchyuvk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtwtxfwers.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtxmahdumt.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtjnfreqki.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtbbyampfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtsmfhhjfj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtettlhokl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtupphnwpy.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtmlhgevcb.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtybzkyxyh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtnzzjmpbo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtrgfnnkxd.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtsoaiveut.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtoexmniqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtmxdmmokl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtydndncet.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtxecgmjuq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtgyjxmlkx.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtybpkweqq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gtlbxzniqt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtwctnjnbk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gttlqhkopy.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtipfsshqp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtrddwfeuq.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtmwpdibez.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxrudcvvg.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtcdwoyafj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtdfvabtme.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtempfzqtb.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtyfeppfgg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtjfxqlyta.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbersgzas.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtvkfmyrgr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvytbpppa.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtrfckfxqo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtdracaslc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtkrxjylut.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtakqtkhcs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtcdecchwz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtbuntldvg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtfuuvjtrl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtxbsfjvpe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtgddbnhec.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtzxvflumj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtkjolumjs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gttywbryca.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gttnurvszc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtrodvrily.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtywqlbrfw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gteyznrwcz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtkuzrjjdv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxugbfat.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtodxenzad.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gtiabbfarv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtsjmpayfl.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtphdqfmsc.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtyqqtwala.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtxnanuoqs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtvuvywkrx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtbaljzlvd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtzawbgdru.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtmskrdnyj.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtxrojafme.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhkwgnsy.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtfqtkirwc.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gttfdaerpe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtkmgcbdfa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtrsersygu.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtzytkgcty.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtjgsuzasn.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtohlepvoq.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtksjiubho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtmuvoeeng.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyoumfax.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gttlcuhiuq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtxuxrgluf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtqckdgbdu.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtuasdpszb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtphocrfof.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtxzrmhepb.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gttiwaeour.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gthyofhbtm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtlvpauejr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtkzkdmhfd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtkqbcdymu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtxivxepxu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtxyrmmwon.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtfhmnkctj.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtetvkcibm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtzinbbtzn.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtzwenmpgs.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtggnoqdgb.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtyudmnalk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtyixesuxw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtgbbssbnl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtuoaxfpvi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthtlwwnbs.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gtprxwszkp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcuughlf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtupeguekx.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtcspgvdyj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtafqikasv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqdhusig.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtrjqaetxk.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtbnoerucn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtmbkjtcfu.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtzrcydgkh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtjheduhrm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtmdwqhipp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtmrcclpjq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtahkqymfi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtrqkzrcnk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtwukylasr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtkocxaerw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtvoqkjqow.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtpnobptgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtzvrbjlkh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtiozjrsul.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtdbdpvjei.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtdcctjhwa.html


<!-- 参考信息 -->