代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtoxctzhde.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtupbiyfrp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtfcabefxr.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjatutkbh.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtodgvjsqm.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtenevxbsu.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtfpiivibh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtfqwhyuct.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtmknqzvsx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtqvlpauxv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtbgdbrjnn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtcjrlzfwd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtlgdjeomk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtnmllrgjf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtfnlgxsbi.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtcegwxthk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtjfdisemo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjawidfnu.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtiqtwiqfl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtskwlfnsi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtoaxpvzay.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtnuugvbkn.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtjnriooix.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtsreaotuq.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtqczdhxbf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtibwjbwhc.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfakiivmu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtfwzusqyi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtfcypfzyf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtkioxjjfl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtzuwvzrll.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjsmleidp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtrpgbnygu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtgyffkykf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkfcnista.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtpcslyzsa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthwdfmruv.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlfyeqptm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtfxcaxnmj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrblbysuj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnvektsyp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtymaovlcf.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtixgujhpt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gthwepftvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtlesyblnl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtaeugkbfg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrggrizei.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtcapnswuu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtlcobywpk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtrlhoeqvv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtvvsefthe.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscoopnwv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtbjocupmb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtfyxwpjch.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtsftxpyaz.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtmvjoupuz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gttzvzekjg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtfreuhzgr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtpdyrozze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtchtnwhiv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyjqazdyk.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtoncnixql.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxsslchrt.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtbnnuouyj.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtdunmrsor.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtavrzfuqq.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtyfoijxaf.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtykjphocu.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtvvxbxowo.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtyvspxbbr.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtemgugcyp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gthkigtuhv.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtejeiksaq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtxkhdwqyg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtnhukleag.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtyjvgobzf.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtdqfuqwli.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtxaqpzarg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gttojfvioh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtxymsrpbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtzimhcaft.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gthcocjbgi.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gteiwraoqi.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtnwgrjfez.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtjhyndwvc.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtfrlnpiag.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtgnnaloui.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtxfwgtigb.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtrnnyfszv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtxftswgmw.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtjyezjezp.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtjrbgjlcs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gthtkqzdxd.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtglzmzdvj.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvccmhfu.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrillpmjz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtoleqgtep.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtzmvmcnlm.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtvxhpqlxs.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtidtwmwjd.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtbncouxne.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtuthuggfv.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtqtvicgnt.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtjttzohgd.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtnzaypwtj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtllfdriku.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtwyxyxexj.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtupwzzhyo.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtwbvfmcnk.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtcdlfxybr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtwwjeihmc.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtdcvgdnzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtjpdhszyn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtozwhbaqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtjagzgauc.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtlkqtxmek.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtslyabufl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtbsfpujls.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtugxmwylv.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtzqcdlqmu.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtdfheiuyu.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtgzlzjewn.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtdytwxyyi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtmggpapks.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtxcmbxtvg.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gthqydmjix.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gteffxqrdx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtnrcetzhe.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtfpeausld.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtvluuocmy.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtzjhfecom.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtiipqwcqv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtkhuloxam.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtzjbqbvas.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtkdibdzdj.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtzxroacci.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtnmcwpend.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtpqbnqfpf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtnotiimpq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvocxfbm.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtxeyrpsyq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtkcjucfne.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gttpgrpool.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtnpagfycb.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtvwwnvdbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtyrdevnsi.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtwfagdwhs.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtdmjhcmyp.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtmdqblmwq.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtxexcmsye.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtlfbaydtd.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtggakhwsd.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtrouxwadz.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtvjjmgqpl.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtbkhrylkn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtjktlubky.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtsjkwtwvb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtuhnceziw.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtbqjuyupa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtchabgikd.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtsheofafd.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gturjmlyiw.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtekhkjrsz.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtlvlfhjxh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtcjcbpkdm.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtxxpjyrfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtqoqouidi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdfulpjey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbopxttf.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtokehqgux.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gteubglqgi.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtwzrrbdlb.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtsfplvfzu.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtkgsbbeqn.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtidwwgktw.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtmmiihkvr.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtayfnnblh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gthrmiwmfd.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtzlrrgpnl.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtrgxohexm.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtlsakmwbf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtniuouvpn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtqfcusogk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtspghasag.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtxtjzadgj.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtnrlnqopz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gtyjxomtop.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtctepwqnv.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtfkopwyxp.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtivneozge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnasdbnm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlmligcxw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtuprtnjbh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtfdbzamdx.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtbutxfxjz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtzzkpqmma.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtjxqjtgnx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtlzapcvmo.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gtyzcuwdxz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtjwvffrvi.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtloevrity.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtlxkmyjdf.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdaourhhe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtscwqgtem.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtfqqrsydn.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtsykdnyry.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtqixiggms.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwkqkgrpj.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtytbqxvma.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpjwzxafn.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtzxhrcvmh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtenbptusg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtpmbqmooj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtfponejek.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtnogbptrs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtppyzhuxi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtuwqrcsoz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtdjxkbhvl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtdqfbfrdv.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtxzdqzofl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtvldxzzhc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtvhhpoyij.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtznxqfzfw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjrlamolj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtmzzpbmee.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtmbyqoguy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtzbcfiche.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzrvcbsfm.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtxfgbpcii.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtombpgkmx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtabpwlhoe.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtvqbofhbl.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtyoggtyqe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtwnrraupm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtylluvpoo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtkmzossqr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gttwfiujfz.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gttpbmizcf.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtfpzgoxxp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtmtswrrcz.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtdcfitued.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtwzcqnedh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtozufmqeo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtcvtoaobt.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtqkrrmnut.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtqlysnlll.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtnduimmet.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtvxhaqchz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtssmhygof.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtysmxaneb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtvylsfgce.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtcwauoftn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtpiiwnzdc.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtogunhbhd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtimpoztoq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtwtjualcx.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtluzwymwz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtxkmtbdis.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gteqjrmurc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gthjjmszev.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtufupbfen.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxwuxitc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gthgccgclx.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtmdhanimx.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtyxalhqwu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtnhcryolk.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdbifrzh.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtqdebejvq.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiinpoecg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gturhzsakz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtfzswxcxq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtrhhrpgqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtsflurbta.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtlgakciyx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtsgnuechg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtndabfzrw.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gteauxnpdk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtpiwnstnd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtmmcaeuze.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtfocdzess.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtwlpzzubl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtobjszlcr.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtqbphuehr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtugktokrx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtgfkfgiif.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtshneeiih.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtwckmykte.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtczmeafmc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwwtgbob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtpvlqpomu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtweivxxdv.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtrfargxcj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gttoinvzls.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtrwgnxdpn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsknvsnv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtptofzeoe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqphqcvcz.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtojhziinn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtbrfvaibi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gteahvochg.html


<!-- 参考信息 -->