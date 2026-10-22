代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gt2eeqpjchz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2gletcaxw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gt2qgpgsymv.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gt2kbxecdcf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkcomsii.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gt2lhhjmyew.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2zejhzljq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2kxhsluig.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2gzfwmhdb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2kogxgcts.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2xolmoomh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2stqrccsu.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gt2gguhxrcl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwteedza.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkndrozd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2yocvtori.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2bbudslpk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2kqahmryz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuoteeb.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2xfeuoqra.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xutqrgog.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gt2udookaqm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ccdjdbmd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2oyldfsue.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2vqlbxicy.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2haijmgag.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2rquroyim.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2qrjwsxhb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ksvpoxnb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrxynija.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gt2ibgiirjq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2izkzknov.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2srgfuttz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2bhcgjzol.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2wdqnkbdg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2ldyofanz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gt2hwhzhwcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2fycxbkts.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2qvdoczmq.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gt2tyjbbiwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reofsudg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gt2qzlaqlxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2sumaassl.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gt2grwiezst.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2tfnqdxfh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzebjjmm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crjolraz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gt2tycemsga.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2nxjqhalh.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2awmbxlyr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ndecrssd.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2lxblvssw.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2oianuenr.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfovmrbc.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ygqgnzxt.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2gvgrzlwj.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gt2urfzarnc.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2swbgreuv.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2jwtsiabj.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2atqhmhll.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2vwteaacl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2pqnrdzzg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2bcfydvwo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2znvwaafg.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2xcvzfjen.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cuekvwad.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2eyucumyq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2gsriwmlo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbhwtnug.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2xuoxgjtq.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2gibdthep.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2mxalfbvc.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2kdtgluob.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2zklsggwi.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gt2nyuukuqh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2cjjzjuww.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2wtizpgdm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2cejoufso.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gt2cdvecggw.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2yghocopo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2vkzmyzte.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vftovlhz.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2gbsexdhq.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2humviozw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2sqciztah.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2tynkmuan.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2hrorbwxl.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2cbhurudc.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gt2aqfgykgd.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2edyhazrx.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xmoptcnh.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2ystfaqal.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2wqxbmzyp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gt2exsmskxh.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2woebrlay.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2iqofamyb.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2oaraufpv.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2lrwzmoet.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2hilxeilu.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2xogknxob.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2piuqxvdg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2ddydylbg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gt2wvnlfiil.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gt2wnlvnwrf.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2kawdnwrd.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gt2vndamzkq.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2drilxgsr.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haftbzmt.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2rkqqlrvh.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2esiwdoww.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2kibhzqmu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gt2mbbbcizj.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpyizvkg.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gt2efllstfg.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gt2xozbuqtc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2vboiwcqw.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2shieawdg.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkvszhtb.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2jxuahihf.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2cnzuudfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gt2pavcrafy.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2vfhrkwsk.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2avvbxorn.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gt2iqtoozpz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gt2cnvefypl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clchyegk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhqkfpfa.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qqnaqfre.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2plilulep.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqjzevgy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2rxminpxk.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gt2usdavccu.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2imtivncg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2itjtrquz.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2nthfrwbe.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2bybomeyk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xvknzcda.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2fyiukkgj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2ljpgprvg.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2zcjvecuv.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvlxujqf.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gt2okvqprdr.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlmknmey.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2jjwipjdh.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2gcloqsgv.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rzurklur.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iaswknkq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2yhmfwsyv.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyctiegw.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2swprgbwt.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2vokflhqz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2zhcinydj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2flenbsfe.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2yzklixis.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2qciaiiwe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2mhlmrnzy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2xxniejhm.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gt2lqjhtxrx.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2tvopijfk.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2ppfzlcob.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzwyfxid.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpjufnbd.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2dupgccam.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2veodcqpc.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2ajdugesu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2dkqyvohp.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2qpayohro.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gt2hdwywjnj.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2uvkfnino.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gt2inmjqzuu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2kylbxhhn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvtxeyft.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2mduleast.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ixoplfna.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykitgovc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gt2qpfxkswc.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2knqbyize.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gt2ovwlqenr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2rxuvoxxb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2jgsenykq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gt2duqdyyjg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2wnhclrqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2btmgeyzs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2umcxasox.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2xlgsebmk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2acagriyy.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gt2njgklnwi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itwujnuu.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2hmwxgkva.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2dbyswybs.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ubckrkcx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2ohqlhtfb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrfaoipy.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2ikvshpxt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2jzexrdfy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2iadsrncu.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2rwuewicd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nqfzjdmg.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2dajakohb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2speuxewc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2evxrisvh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2dgkmwzxs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2umkovzzh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gt2kilkiyxc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gt2mudxmwcy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gt2bvvmcqjf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xywknfcr.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2ghbvvaky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gt2ghrlxfft.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2llfeiyxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2nhrvcvau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akwtnrrz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2fbmbuqmx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2oquurbcu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2hstipwbp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2jtdwqtdw.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2irhscrhw.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2ysdneagk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2sbssdblk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2ljgesfvr.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2ikflouok.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2ycnxqojx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2tysglpay.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2fnazudcj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2lgnwebnr.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gt2qhanubhs.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2szaqziqj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2svkdompl.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2hgnemjhl.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2doxfjwpu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2dyfoyult.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2snazuvvg.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gt2bmvakxlv.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gt2bkahwthe.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gt2ttnxrxvp.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2tububgqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gt2tciiqgkw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hewksmcn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mluskzcx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxtdrphe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrilatgl.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2zkwfrnoe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nnxnyhax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chegvzjq.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gt2konkwvgk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2foatrjud.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2mcjdamva.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2vooqtpuv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2yidqugdq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2jmgirzhh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gt2ugrxbmfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gt2zrzmvjqu.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgckbofw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gt2lxtwmrhn.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2vhlnxhva.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2unjohbmo.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2jvfwafgf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gt2mrfrjqqf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gt2lnesfmnk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2qauofpjp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2gsnkrdny.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gt2zwaamuxo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2prlpgtug.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gt2djnuddyi.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2oamnwise.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2cfeqsvey.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gt2afehlcvc.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gt2mzejfane.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gt2yxbqpgva.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxidvfra.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2cfkqtkqo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gt2gcsabahi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2psrlvoro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2mpclxqrm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lojxxhnb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pepcnmsq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2sdbiiskw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gt2cnujlleh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2nieervvt.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2vsgnxwrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2txoxautz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2iqkgdmnu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2elyxdbua.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2xgcqbrzz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gt2ecpcbonx.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gt2yvadxjzm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbcatbsi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2nwvexuhg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jlvprcct.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2fbssnsqo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2blojcvuj.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2zbyhyigb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2icqbprvm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ansgorjm.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2oadlzwnt.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oupatsuh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2snybngeb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2jtobxlrs.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2xdecljdg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2lspnytnc.html


<!-- 参考信息 -->