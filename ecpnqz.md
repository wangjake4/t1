代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yiyvudeo.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2liysjzna.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxycgtrs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2ahsybwgn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2yluntwil.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2ulhiyhyq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2pckiyatc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2dxxezamw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gt2evcjwces.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2qdvrxncr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdskzeau.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gt2mybhqfhz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gt2ntsrbwxo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2lfxlwyqj.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2jsqwvtrn.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2umieqknr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2pgjobmdc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gt2qxmaobkc.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2tmfdrecs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2pdpitciw.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2odmbrjqg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2suniutpx.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2zvtbidku.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2cuhzrozv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2mcllfoxu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2cnigdagb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2hljobkmb.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2jnofqghh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gt2oamxybtt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2nacophgs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2zkpjqize.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2deoeqtnl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssbaodjw.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hfmqblvd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2megmhkhk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2gefzmomm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2nczejjxk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nnlagndv.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gt2hknkqrnp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2lwgxcjzv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2bcgzrsoe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ohqqbdnv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2kunjpjpt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2umznduey.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gt2wexrtums.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2rzvehyka.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2sctfjtnd.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2xltjckbp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gt2arugbwyo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2marrznck.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uttfccvk.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdgbnodf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2nudtiwcw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gt2ynwdefxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gt2whjnasbh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2rdmzuyfv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2puwixxcb.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gt2ubgmbcst.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwisvogw.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2ezswjeao.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2aozrnxzu.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bctxquna.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2nokytsex.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2ebxutlrx.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2msoxgdkv.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2snxkaped.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2nmzmpket.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2pobmvzuw.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2rdnudksy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2mthjbajp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2iaofaagu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2sisdbbet.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2aqoclpjj.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2tsgcpusf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gt2rglnkkoo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gt2kuruziyw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2rujbmmxh.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2pgeeeqkp.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2jqoxanaj.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2ybfkgbnv.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2yyysjipz.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2pkkrifql.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gt2azfneyzm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gt2tvrpcctd.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2sehijecd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2ciludvhr.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2xruzvlwj.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2trvdlude.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2onhddwvo.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2xnqxtoiu.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2ugprvxvu.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ajqxxlxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2qhvqnxxh.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2exwfxucw.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2yiofakit.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2uelnubzn.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gt2qjjilfgh.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2cbxstzbl.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljcmfdhm.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2hrtedwre.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2scxrvjwk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2eeuqlcbj.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlfueeod.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2lwsbzdud.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2zhxrcatz.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2tsvlurfr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2fkqlxtun.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpjeztoc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2fsinilcq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2vuctxjzl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2zwlmorng.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gt2vrcdtkgm.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojmolksg.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gt2whlhwzcz.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2msqczfld.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2wjyqxpkk.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2vbvlplhr.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxdcotpk.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2mcqqzbee.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2hmqqtukc.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gt2xjeqacdx.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2whmygxux.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzwfxhio.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2uddldqoa.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2jxxrkuhp.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygdvbrfc.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2ujxohgwy.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2ocgvidhp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2hknojwbi.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2qkxvunmk.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2jkfekqvs.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2rejytrvq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2nuypwzrr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2adviphhs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2hpauiyho.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gt2vxrdbhan.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gt2rdgagfea.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2fnznwkch.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gt2nkunsmkd.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2eqlyliwk.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gt2bozxveim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gt2bpwzidvw.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2lbpcapso.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2ktqmakbp.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2ebxnxbkr.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2hcpdpqal.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2tmtiekxx.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2kmdrtkdh.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnljmnef.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2tyfrqtor.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gt2phqlydgn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vopwwyaf.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gt2xaijjmka.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ajtldasb.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tphvogpl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkewpmc.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gt2ypujjmwu.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2nnkjknnk.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gt2lzidxexd.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2xnjmmmth.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2xdcfoxsh.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2uloyfilz.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2esllmqes.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2jrsheyrt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2nvqatwvl.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2sswhjowc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fudqpduw.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2xwlnucnq.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2gumvbdta.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2fehfdtwp.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2ukbmzyye.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzvxywcs.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2fpcetjpp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2llgcvqln.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gt2ydmiwtsr.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2ebkggvam.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gt2uhwuowzk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2rzqztgag.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gt2ruehslue.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guvluvbn.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gt2meyvsldb.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2ukfnqanv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2ipnnbfyb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2xdqbsehl.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2ikenouou.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwiwbajh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gt2anmhrbgh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2veozxmhj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gt2mifwumsm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2ugqgtxsd.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gt2hetivjgj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gt2kpjzlzee.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gt2vldnlxlq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akaihmph.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gt2mrgawbsu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gt2evgzismh.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2nqkohajl.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2fsdyywne.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2rxlujrih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gt2rvsfgree.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2cicsxayg.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2aylmvxtk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2yfhbmker.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2jlkduivr.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gt2tihontvx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hiuueyds.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2zjftaxqk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwpdgppv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kyedjqiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2ljbgusrx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2noragoyk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gt2cibcttem.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2gzajlmpq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2czvmqady.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gt2apycyyga.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2naayrbmt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2qnvwijfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofgazbts.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2epwjwzrz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2mhczmvnp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2djuqxqxv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2mhqluwye.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2zsewtwvp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2jecwzuhq.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2xdmkgobg.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gt2yhzrtaud.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2zbysvjnu.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2mwcdtvgc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkgjkvoi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2nxwzsuzg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gt2fsuffzmq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2iixoqmxg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azpvgzsm.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gt2txlfayal.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gt2hwaoofqu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2imcbzoii.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gt2vewbcejm.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmkcdorx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmxdqsie.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2todjnutu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2hmrfhlke.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zgymhmxv.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2bckpkcti.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2fyvciyfw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2jvezgdkt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2ehtfxepn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2glvyozoi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2aouiigzh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2ztffdzqm.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2ekijbjdb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gt2izzcwlic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2uzpzkvsc.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2bszshqmc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvezvmpo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2ysefetkt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2qittbjgp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2ujqzctee.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcyqmlia.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2qmddtgnf.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2bwcxqbxl.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2xohkmodc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gt2wvkxpphi.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2eahzlakv.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2kflguard.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2qtdfxeiq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2ikdafwjo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2mkhlgirf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqnulapq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2rztxbonw.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2lttzenit.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2wjypvvsz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2byuofghp.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2hzxemllc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gt2symbmukn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2maqcpsfp.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gt2kteleggn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsclaudb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2karixpjm.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gt2hskcziui.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjdudovo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2ggrumzvg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gt2vcfsdezs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2hirwlnog.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2asxdaehf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2zfclxabc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffbwcaji.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gt2wqgxuump.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylvjutva.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gt2iaiflgrk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2blxmcgom.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2trjysnuq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2imvpycyb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2vvkvmaln.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gt2owwcgvaq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2chiojcbo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2olcxcqbu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hzxirzbm.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gt2jxtlsoiy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2nnnvtzri.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2ifmmtqac.html


<!-- 参考信息 -->