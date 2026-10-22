代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2hivzhxvt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2khdxbhhm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2jcbehagh.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ltxjywjr.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2dijikeuk.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2crwinlin.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2ydpqoufl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2kmfdvcsr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwumgyzx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilpvhvfi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2luynjwzx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxfybyqh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmyhkhts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gt2wxjqxwux.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2pqgogqwz.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gt2jmafwbhf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuafdyuq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gt2lfdrppcb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2aleaiirn.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2trnapsnd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2pvveipiu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2vmyzozmo.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2yvdckcew.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2mcffexoo.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2ghuyqtzj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnvsvbud.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2cgwonibz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2hecyodaz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2dfzksvwz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2lnjpkhkc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gt2xxwhknjt.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2xpbcmuav.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewqnlbzz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofovmblw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ndwhamfg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtmiispp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2guiovfes.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yxfikedr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2xzhuiyln.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2irucuwzm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pywuxwqu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2dsokfepf.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gt2lfwbrvbn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ceeaoipv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2fovtpxng.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzkzbsyn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2cnxiebms.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2faspprsl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gt2jsvdwmwz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qbezakwe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gt2paoltatj.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gt2dpsaeqyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2rlzruktx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gt2jcpqcgvx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gt2keedxpec.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gt2igzdrpld.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2vnzpxkqg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2knqnzaci.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2kzgwfhaz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2jbwbguoo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zcthnjvq.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gt2gamyeygs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zbqkjddo.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2tcjychrd.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2yyivmqrx.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2aukzqfok.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2jjyreyom.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2wkenijla.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2qilocwjp.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2wfiapviw.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2nemravow.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2lccrbjyy.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2bzkrjptm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuemoott.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gt2cftlvkyo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aifrcoik.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qiuxojhh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2fhpsfnll.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2nfjykltn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2wudlfxmu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2ikunquvj.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2nzgumjiw.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2cnveohck.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2wxgwppuj.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2hajvvjzc.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gt2fnycmuyz.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2ldutloji.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gt2ofshzjub.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2nihdsjhe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2kmrvzqvy.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2lssnceha.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2okzmztma.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2fuvoxaoy.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2cqowbhpj.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2iovxmyet.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2hxpoedkb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2zeuxxcsf.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2kdpztacf.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2bedukvys.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2iiwreszi.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2bfmoilpr.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2xvsayjtm.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2nfcdyrzg.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2ahouhulj.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2twqjggia.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2mtyvtoul.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2uqvrpswg.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gt2hsshgkhc.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2vgzrisyr.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2laxllkww.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2itwhsien.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2mtanbici.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2fzjljflm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2chsaasvx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2dvekhenq.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2gwetwoky.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2ylzlkfwi.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gt2rltltiuy.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qasgytbw.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2gfddfhfk.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2nfoyqyup.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2kypzxiwo.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2cvjvivee.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2bxauuakq.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gt2xfvcmpcb.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2cysmkwsv.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2bqfcstim.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2uwlbrfkx.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2xoupykwc.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2qxbjbqse.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2glogputs.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2dkpwisoi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gt2jigxdzqr.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2gybnqxyg.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gt2dxecgqmo.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gt2sbtiodcp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhjkrorb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gt2craimhnc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxgfaivy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2qzxfyozv.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2gmvhdmve.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqrbljxl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2zslpzbyf.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2udmbqkni.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gt2aufuxfzi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gt2glbghsfq.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2udmqsoan.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2mekpnrvl.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsgasihu.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcbchifl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2hsnuuvst.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuvvwodh.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2zysiyxmg.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2topeppmc.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gt2xwbsfksz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2uydjsrfb.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jtuqyabb.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2zhvlhsrf.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2ovncfnst.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2eaprozwb.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2bcorptnu.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gt2uwmioymh.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gt2lwyzzbtv.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2htrbvrwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2wvuadffy.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2aoawvoyx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2saxypzqx.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hpfreibi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2vguvkckq.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2hxjrvuov.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2owblpprx.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2dzbhnnuj.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gt2aagpejkn.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2uboinjps.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrkhegrm.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2qiwusldh.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2xwabzhzk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gt2mudwceca.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gt2qillwwgd.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gt2jibctbyz.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdhsgxji.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2vldpovdm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gt2txgcynci.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gt2uqsgudnh.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gt2qqsgqdpl.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhlltxir.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsehvgxm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gt2zsehqtal.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2xyhojnst.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2xnycpxbx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2lrahfclz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2odfcklrj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2njrrqmlv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2syxtfvnr.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gt2agjrkrdv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gt2wbqpzsqa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gt2seinneef.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2nygulgoi.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2xvfxodsp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2edzkfmgr.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gt2zwkhbsxe.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2kapduzlj.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2snzkfrov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gt2ikvalwxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gt2hzanvvnn.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gt2mqnooquy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2tonqyfkv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhnvzyse.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2yryuyzol.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vpmmqbws.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2heqpyeri.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sltpdpxr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gt2mivlhooh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2tkuuknjf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2kyfsthfy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2xksxyydj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgcqseoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2bvajinam.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2rogbaezv.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gt2nnnrvhnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gt2qafdewgl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2stwusdxr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2sqoeuocy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2urzfpvma.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2nleiitne.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2cdkzouyq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdrwjilz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zltxbwpq.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2vriiziwa.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2pbzlycxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2anoxegdu.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2iuljewhz.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2idmgbimd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2tzzskthk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gt2infmpiyf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpqixqge.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2cgqttvwa.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gt2vprexocd.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2qafhamzd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2qfwuzahj.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2olpfzejb.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2rbvmmrpj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2jumwwprl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upolkovc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2wpizwrkc.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2kgshlanb.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gt2tsuokbdt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iblzcwvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2prrxfyrr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2mpyuxvvf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pngjowiz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2kphjmeuk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2izxpwydu.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2ngzcxpdz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2cvtbmzwv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2sjsfeeko.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gt2nutscdoy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2vuwiysyz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2mvyvehao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2weecreqt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2gupzldoq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gt2alvfkdvw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2kocrygyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbpauxrv.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2hiewxpjm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gt2cwcxbyud.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2aehliquj.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2pjayymwn.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2dtwhjcni.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2groolxoz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gt2ivttszal.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gt2gfvsdlhy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2lmzzmkgh.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gt2xvnditbo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wozmcmkn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2xvzckuir.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhlrezkz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gt2ahpjatpk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2nbcgyeos.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zordsktv.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbilayzi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gt2lsresktz.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2ysqydjvg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2tszekxqu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2rgbtvfux.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2mprvxxtu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2otwrqmhr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gt2badtnyyc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2wwgzkigy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2lilvivsh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2qmioosch.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2ykdwagpg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gt2vctcgahl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2kgaszdja.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2hlqwukfh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2mrcivpcx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gt2aorxxyel.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2hduanant.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gt2nmxzgqxo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2sxydgqmr.html


<!-- 参考信息 -->