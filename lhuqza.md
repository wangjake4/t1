代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwiqcurif.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkdxhugze.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtahrmumxh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtsiycbfcd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtdzmsnqhz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtguqfqewn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtydwydgun.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtkejntkgu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtjxbemmvk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtnubgpsmr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gttndzjftp.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtiyglmaac.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gthobtjvbe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtjrskedob.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gthgkxfkcy.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtyshscbbb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtgfccothw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtzmdatvnq.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtayzjfooi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoskgork.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtcuodwrzb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvqxmkmh.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtvdgsyjpq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiryyktk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtekxqmxgt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtoeeenidk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtycgojcpw.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttkihxjtc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsupwaiwt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtrppvjaoo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtgwwsdrsr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gthvrlidht.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgfrqxzje.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlcnxcfbb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtkhrbqrum.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbnwdixie.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdybnwgsj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gthtnsxkxg.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtyzepamaj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtkafylwgv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtzuwxwzeo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtmwsjjmze.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkzhfkbfd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gthnuotaok.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtulthngqr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtotbivnym.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtacqtjotk.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqzfgnow.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbehsrhzx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtlesankpb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtzyzckqhl.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtntghtgnu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtleakizxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtqxccokut.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtzuaujlke.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtxgeefegl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnovrkpvj.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtfihztshr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbsbnhinh.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtcqwyhuma.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtzsbjaglr.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtzjookrau.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtcuxobhpq.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdtwfsob.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoviawvos.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtuihuqfzi.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtdbffhhrt.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtedvdpgmu.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtgvpazpid.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gthhgdirkl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrvtusgc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirsszaol.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtmzhnrfuz.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtybrxnpwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtdzmwmnfq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtdsyqzygs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtxlhqhadd.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtwibjtjuk.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtjsqjvpfv.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtfmtxjnjq.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoooasuyn.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtzzbtteef.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtmabrtxyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtsdmkrcqw.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtpmdjspac.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtrvmwrjiv.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtfdvkblrw.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtwbsogtty.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtaduhwema.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyztrjfze.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdedkcnvn.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtflqnigwg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gttpfuetxw.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gthezokkzv.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gttdahdjcc.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtsphwehcb.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtrxwokmok.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtvlbgbgfw.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtrumjkyvx.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtpecempzf.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtmzaegtce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtwjytahsn.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtfhirvmij.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyikusynk.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtvhvolsod.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtqjtocdzt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtpjkrleah.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtoorlfhou.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtyjprwqgw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcogjohnl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gttliwnocz.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtruvdpifo.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtoitaubwu.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gttqkrqxzk.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtymirptrp.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtvjxdnpyd.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtggnqohcy.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtepoeujgz.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gttzdbwxze.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtuwnfooor.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtwzpdicxi.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtsdslttsn.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtunxejbte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gthzkectsp.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtsqylryzc.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtcmpzeysi.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gttxaqxtaf.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtlbcrkhck.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gthgqrnwri.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtdhcuatdz.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsgcbqkto.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtzzhsausg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtfggdizms.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtelgyxrkw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtteszqrll.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwsflcdf.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtwfqacyka.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtjyouvndb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gttlkanrup.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtijitjxls.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtvrnqldcb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtmtuokjyz.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gthgsgfsro.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtejvoiclr.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtcryypfng.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gthcgdnbfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtvyxyndmg.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtuxutbsfg.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtpfidptqv.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtdvbymxts.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gttefkcnfs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtbugdcpma.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtactxlibe.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtmhxvggdu.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdqykerld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gteufocmov.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtxvpvzwnj.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtcfewbzxv.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtjqutvset.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtluidvlou.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtvyvzvwcj.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtwclnvysg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtrxwtdhpx.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdpejojsk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtvypztayp.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtngxkhalh.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtushcsmqu.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtcuyxxpti.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtdxmlaqpf.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gthkpnyvun.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtlljdqmmj.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtmdtctbij.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtdegfhwoe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtznvyqogz.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtlvunyiyl.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtxlkwjklz.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtvjzrimtb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtbjukqobt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtgjnghzfk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtyhwudwvd.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtcqyabkbm.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtbztjmbyg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtfkzyjuig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtrffycxwo.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtaaylbxed.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtgppvbpko.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtvicppzsk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtfqjbxelr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtinxsxdcq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtiafwmvzi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtawzohhmn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkzaqwfu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtbqpcdnpt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtscptzdac.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtfaartiqd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtgpnfbuub.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtljygdhbt.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtjyyvjngs.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtjwwstcuz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtndxafdhd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtwuoneqoq.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtcnxdvkto.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtpmgremxv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnjrpfqmb.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtmkpfqvsg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtccivuahr.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtzgmcacnv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtepqytpaj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwugzgatw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtmdrxwzlp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtgomdmlep.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtfbixcviy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtdewucqsr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtszgtaqqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtceiwytsq.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtaqqjflxk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtsineyitx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gttilsszja.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtabnredcd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjvawcogw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtghanfvlu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtnxxofkjh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtqgwurpvu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtgkmhtnxi.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtifyjtfit.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gthawdlghg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtnwowmnym.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtddnnxmof.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtmmlqygml.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtosustlch.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtfwcamatj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlytdhic.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtfhxnedzi.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtcklzxpzp.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gttmteheie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtycaypwge.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtoxefychc.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtdcdoqddo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtptqemfoe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykaaoivl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtzxwqbfle.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtmhdxkhfx.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtffgnncnh.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtqtcaprhy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckjcanxe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtjfsfeybz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtgyhenbxi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtsgdccgss.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtpalxyikd.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtqckzymuq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtbhhlnevr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtuibaruzh.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtkfvmzpta.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtdlezbrix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtnksbddln.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtggupdxwl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtkjkbwacq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtasvcrskc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtxixpkafx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtzomeqhje.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtdvomhloz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtwpwvkpui.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtuqdmqbrz.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtilpvzwio.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtsnakqvau.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtwmfxdsol.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtkriqroay.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gticxjapxw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogsfulnc.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtypijhlus.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gthgvthsly.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtmvhjjzks.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtnduahszf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtsbqjoehb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeyygwdo.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtzjoyakcj.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtxagiksmo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gthryupwcq.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtgeogdxpx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtdhbqojsg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtljlefsma.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtjkgjftut.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtxcjznrqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtnuudhiqk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtsahtnqkr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtrzfjevju.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtcalgkzyn.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtliwflpcv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtfrwxdgvd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtroojhusz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtuaagiogo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtssuisifg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtbdwsimst.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtspxttzxx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtppcdfvzr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gteynwzalh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtztxjzvgk.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtenlgoown.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmmpviiaj.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtyedjnkeg.html


<!-- 参考信息 -->