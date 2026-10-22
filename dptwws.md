代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2quocosth.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlcomnnm.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gt2wdyupygx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2tseijtaz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gt2lcvlxgif.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfvyecle.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2ubiibhfu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2llkxmfzz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwijpvql.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdkujeal.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gt2dllxwxlr.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2toaececo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2rbbutudy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2duatwtqj.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2nbpscjjg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2ihljdzqt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2ksdetwwq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2kfxfvzsy.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2aagusvrb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvvtxel.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gt2bwuhflau.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2odzcgexl.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2sftqiruf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2bxmljebt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmqganlu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2jgmlhelo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2gcbabevq.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pnmliufm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gt2agpjkwqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2oksajjkr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2xjioalry.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2pmsflvva.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2nhhwtjkz.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2icetiycy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gt2fandgsjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2jutrfvxu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2dhnskjdz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sytgwbxo.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2zkwqtqcx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2bmbfzccg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gt2iqpnimja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2jftlbwvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2fqiadxce.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2hzxkzfdm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gt2ztyjstrw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2ejehnitc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2zdyydglr.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gt2lbnigrbo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2dxalnxvv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2gutegbee.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwdenngx.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2uqovqzmj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2bzjuckvx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2vrvscudk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gt2oqkxsedd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2mnwujuiy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hirurfno.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2rjglifxb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdeluunm.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2fzfozcoc.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2njpudmpc.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gulkqvmk.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2mrcqlrki.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gt2ycnylkaj.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2lhdlctdu.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2xwbpuvhc.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2cjygpsdu.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2xhagnhia.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gt2csqegkrk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2vzutofdp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2fdweqnjd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xjcpqfmg.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2bxbyazma.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2cjjtooif.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbjxzryg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gt2lbipgihh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2zeobtafs.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2nstgwhie.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2yzgtlfbp.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2fiqvgdyd.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2vggxterj.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gt2hszfijqz.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2edzyxqhw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2vurcypeu.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2moupecwy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2nsimitdr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rasgjzet.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2basvxxba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2cyajjdpx.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2gymmfmnz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2opojjfcq.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2eofvfzqc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsgebplp.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2xcwlrhzb.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2ecoupong.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2galjhsqx.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2klkdmrzk.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2pkplgale.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2bjokktyu.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2cglqczsu.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpvwgnlf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gt2sihphbya.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgetxgqr.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2svckryuq.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gt2dvgksjtx.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2lgycsbpb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2ciitgdxk.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2veyphzli.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2loqzbile.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ryxmdbfj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2bjwreqgo.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2ogplyrbj.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2cyozyxri.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2jfiilcus.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2blnvtjtb.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2kxatpshl.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2uunlexqa.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swiukxfx.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gt2nlaznngc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2azxcaipe.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2tjnbgrib.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2gadzudej.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gt2henztych.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2ijfovina.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2memktawr.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2ulofrjkt.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gt2mvspbxgw.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2sejyxuwc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2ujhxsweo.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckqgpdzk.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gt2hbcblzop.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gt2atmetnxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2eybffdky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2canjytge.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2hbphsbcm.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gt2kuexxllw.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2tvizdhxn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2oukizkph.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2kshrnfct.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2aqnbious.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2kaqpffdy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gckcacja.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2isyzoisa.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2nphkzelb.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2heovxhgx.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2ueavrwma.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2ujyyvdvq.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2wgriwshu.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2dpkgqjmu.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2pennenxn.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gt2acdonwmy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpuyrire.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2dnnanczp.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2grwmozbm.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2moeeckak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajntchqz.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2qxyziqlh.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gt2uexjhomi.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2ggmtpdvz.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2cyuauhgf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvbmjpxs.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzirkjcl.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vapqcvgu.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2zaajugxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmmyhnyu.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2sciztrhj.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2uzxpwrnr.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2fvxxsycp.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2lmozkvxo.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2vejjqwfh.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2nwdgeyiw.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2rgqktdlq.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2tkhddtiu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gt2mtnxjfne.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnllxtfd.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2kerdmonw.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoyhljry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqguvujm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2wdqvlqmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2pfhhsytk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkhjdjyg.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2koykxfpr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2ultvmdkj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttelikcs.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2hhniccvs.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2tlitfpnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2jyoqgcbj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2tgfqiqxt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2uzfhbkdx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2byvvomtu.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gt2ubkeejqp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gt2ehizmduy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gt2zdzlfdgx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftaitmpz.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2rxaucybr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gt2ogckfuar.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gt2xjjhsvmv.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2zavmmdzy.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2bhqnhmma.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2qywtqbef.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gt2gyqbdiwp.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2wqkgqopp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmmcdsce.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2uzuirdfq.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2govgjjpn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wowlcohk.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2aftxdirx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gt2dfxxjvrz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ezzfkhbe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2xqrbohcu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2gvptmecy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziylytca.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gt2lgjkjybh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yydporzr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2dypujzwm.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2wuzrlvhf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peghvleb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2jzlzabhq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2vbphtyue.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bdbircgf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2otdsquav.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2ghuqolhk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gt2rnoooruo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cibyupbi.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2vxducbmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2zdgliikq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2njejcjvv.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2xokwjbyj.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2kfvofany.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2zduwwkla.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gt2ahjxhqyz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gt2tdamcnqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2mtwhsfab.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2jzdispmt.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2fytgiltn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2bdbvfjey.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hseiypul.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2emcmwxsh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgjcjizf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gt2gudxaoaq.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gt2pkyfnajy.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkqodyad.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gt2xkbwidxq.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2izmcqcjh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gt2ycwutnjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lopykjpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2otburszy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2dwofsmpw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2wcfxapfu.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2tbkhmpit.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kydoyfya.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2amzahhyz.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gt2runvondd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2wicvrlza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2ztajfsrl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2tzwzkosr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2jyjpkath.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2dnbmolbd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gt2vwfgnbye.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2nfdvsvnu.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjyvclug.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gt2erilhrjf.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqjmhikc.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2gsjrfgdo.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2llufmbxh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2hxtrzeao.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gt2ijdlwzxd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijdtcomr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2utkrxlzt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2ublbenmf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2jvmuftzd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2khixwfqa.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2bxoizkwl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2yjllczzf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2lahfilbn.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gt2hdhtrpcp.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2utbczzgz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2snicerrd.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2gkawnmfn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gt2vhctdwbc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2nhexeulb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2xzqmnggi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gt2yftzkfxv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2giopgvzb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2goyrcwtn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2yaufuhum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2whpbbaih.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2plowrbxa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2mnnlnpll.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2jnjdnsvf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2gznykksw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfurevpv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2tuipljpa.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gt2huwsscqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2buuswyna.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2byljgzih.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xgvoymyb.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gt2ffzftqsv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2qxasbvpi.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2izentlob.html


<!-- 参考信息 -->