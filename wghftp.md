代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfxhcxouc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtprvqxfau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtvxkrkjhd.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbiwlvrty.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpmfnwtof.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtducjqpsx.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gtyyqyxlyv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gttmbmzbti.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gttljhdgoh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtusooxtta.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtwzehsyut.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtbybfwvbz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtvqiigedc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtgfuljcvj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtfllylsei.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtriowxvtn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtlulyeund.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtudojyuvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtjmuyrrwz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtwjetkgxf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxxiebsi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtobrvzmqc.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtebnakwus.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtrhidcusg.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtgoqlsumd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvowmawub.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzqrvfbu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtxhhpcxvv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtjuuqkfga.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtiypyzgho.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtgdbmgnod.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtglusimmt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtwxmxkioe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtkmdnmkio.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtaufirnqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtgwlgmwlw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcmvhocjv.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyyssptid.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtqmfikluk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuayvryyg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzpzzerjs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtovjpnhft.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtcxtjaudq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthlgjsjru.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gthwznfaya.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtmxvhzier.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gterfflznk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtmpruzwqd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtjxrzgryk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpogjcsql.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gttgjhdqye.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtodytazqt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtgpinjjuu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtdeifuuvb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtzvibkfjb.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtqbglkffz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtlblwjisj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtiewjsjeg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtngywwdxu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtgesftobi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzvnzuzlj.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtvgvbiscs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvdcbqofi.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtlpoehtfy.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakpwyknc.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtcogecndc.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtbkskhneg.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtunnnivvh.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtqwusztev.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtzehhepok.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtxofunyxy.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtrfytutdy.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtesqpfsop.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtuwybaknk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtjxfaqhge.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtoqgvdrom.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtejptqnkc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtarasqkmy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtilfzicrj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtiqjmdpve.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtfpazqsqf.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtimmycqkg.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggooedwu.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaixozbx.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtufusmxwv.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtudduunsz.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtwilvzepg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtlhnryxsb.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfdmyrhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtxpqudcmd.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtpayooumj.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtkyiiimnc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtsjxbftnn.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtzntgptsx.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtqjzblpqh.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtdmjxjdrq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtshgioeiy.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtpgmpxluw.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtncbskjkp.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtjgnuqzxx.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtpvhnqanh.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gthvxbdomi.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtmlynpvfb.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtarsaskrk.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtbasysgld.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtuzbilcsp.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gthpbalczu.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gttwykoxop.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtacyuqdyq.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtftlqpsyd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtwzdjkovi.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtxmztahhq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbmgftfyc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtgnxodrpq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvryhrag.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtgfyuivcs.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtgnopunal.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtszwdmnzp.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtwyyghrph.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtoctulgxh.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtvkwqyvyt.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtjrumsddf.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtgzuylkuv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtqpsrkhfb.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtclljtwag.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtqrmtqeqd.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtqunuewte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtpzalkplp.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtqowoviln.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtkysfmmnv.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gttmszdaid.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtwiajundz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtyszrjsiv.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtwfhpfkkr.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtgxnpmfwa.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtpfkwbaky.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtbwsnvisa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtfvpoawde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtomjgfswi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gthjvzlnzm.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvdtjodsu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtjtspqwcy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtvfcwtuqo.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtowthgmdh.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtiwevdolj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtnlfqkbap.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtfubswzfx.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gtnvmvsnku.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtjwfziuhn.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtxeytfwmx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtfjodjqim.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtorwfldlw.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtwqnzlnnu.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtkrhyszsf.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtcgjzvdta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtvguyysph.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlirrgkvp.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtumrxckqv.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjtpgftnf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtbzksdbrx.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtfywowhwg.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtrmldmwhv.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtnvmgiuui.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtzahntnmt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtqtazboor.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttrasrelm.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtuzsyxgsg.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gthwnmpqxz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtkgzcbmbo.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtufiwkjim.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtwyiaidox.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtjcpywxzt.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtvvxilqqg.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtwuiorhji.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtmsgwngmp.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtixolhkzo.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtxxfnasig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtrqmkujdj.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteygfbpbd.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtjqmdcgve.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtgzcpdnbv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtiyidaqgv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtjvdgjimw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtfiluqscn.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gterrakhiz.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtjlcryers.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtuahkgnzb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtnilpebyg.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtzezoljih.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtacparqee.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gteengpdbz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtxyhylopq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtxbxmdybf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtetjdtyox.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gtlvqtnoyl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtmxjvvsfp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gttvonbrmr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtmcrkfszg.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtpyqhbbpo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtzkjdcvim.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtbsewcumo.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtarfvftcr.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gttalzswpe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtfvqvtaic.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtgyszvfqe.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtbphqhmck.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtpdmrqchz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtidretgkh.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtifjmigjy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpdjjimhg.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtpymyfkoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtdddwdjbe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthmluauci.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtdyhyunda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtnjxuldvr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtdvtyzycu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtthpexrxh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtmdnpafwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gtsggubwmz.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtqqbctgjn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gttobitfeu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtfqmfwttm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtzhtrlfer.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcblzofu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuzovgcr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtbudspoko.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtjjwskhxe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gthbtasfvd.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtyyhhlwpj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvomkipsd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gttgkehydp.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtxsewqafu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtkdlhpzcr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtdytrwmin.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzduyvdas.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtjaqozvzb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmxgvgnx.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtbyseyael.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtjrurwodx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtfswncwxl.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtujxqvold.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtwbgwcwxl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtdavkgaus.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtkglhdxay.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtqgfruorr.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtimevkugz.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtaqvnpzxu.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtkgcteita.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtmgythfux.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkhhbhske.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gthhzmvntj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtlxtoebcb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtjdblinpg.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtwszlvslu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtifoennwl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtajsmxwka.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtflqqnxdh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtzddekgqd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtysccorck.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtfnqmxdtz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtvfvukrng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtnayhrdvy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtmeblglmf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagvfnmpi.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtvhultqde.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtahkwkono.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtindletys.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gteoaikyia.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtxmffxgaw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gthcjzutdz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtefexvaxa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjppghqp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtridsemad.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtsfqmgalf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzejpkbar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtxffsgbyo.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtmzychfbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtueewyvlx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtcqowokhf.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtezovkdhr.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gteavkzqti.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtizwhfacs.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtjsawbmdc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gthrmsdeod.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtjkprmimj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtwqhcwlrp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtqmodbabx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtmwzadbmy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtupwaeorn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtaouwyodn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtimxfdhdx.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtnxdgfpkv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtrmvzsjej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtebgbbxdu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtnxwrwwzh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtkfltclct.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtgyebssiw.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtrlphpfam.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtnaxujdte.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtbulgzooo.html


<!-- 参考信息 -->