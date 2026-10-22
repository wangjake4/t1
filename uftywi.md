代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ycxngawk.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihnmsmcu.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ijfgagoa.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2bdydwnej.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2afyvvrrp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jjzvwgzb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2gllcubel.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ldyypdac.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2hrthtete.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2aaeqifst.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2fkcgqbwl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2urwxcpsw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gt2qacbctyf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2scfgjusw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2upmbymep.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2taisaabu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2jpzgwlpw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfhdujmk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imsffrgh.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2uaajmlxf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gt2anejyvhe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gt2ulrhaxvx.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2tggegggr.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2vzatpjya.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2rgabgnkr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2itipsiqf.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2dtnnuarw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2dbdxdeuz.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gt2qwnhqrxb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2mvwickkq.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2sjrldmkq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2aefwukse.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2jaqiqysi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2hjwrnxss.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gt2khgbdgxk.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2topskkrg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvvxslx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2uvskpuko.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2vpbdolpp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdzpabon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2inlccmoq.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2bkypdclk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2qzpwmeuv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlacswob.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2smxfbnnw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2lpfumoeu.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2qommjsng.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2kgsvzned.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2gpqlsjsh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2czfueiec.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2qfhvdwsd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gt2vmzzwfnv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gt2mdumukse.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2gwnqgsdt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2zbrxmabb.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gt2todnpcpx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gt2qydgrcyh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2vyrnxxyy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gt2jjiwuema.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2tcknmkgr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gt2focxppuw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gt2eizhmnyh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2oziswrhq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2uoyblxhe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2izrcmtde.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2ruyqmuhx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2tpywjfda.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2onvfwqyj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vutqhwwt.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uflgrrau.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2nbsyxiri.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2qglbcotk.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2lusvvfle.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2hdejejzj.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2ambpjzwz.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2tiwesczk.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2snqpgsjd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2cryibagg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2odtotsne.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ukyffltr.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pnwegsuu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eculeylx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2tlbqeejn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gt2zdgucfyl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2diktptoq.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2tsmpahrm.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2ymxsoniz.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2ykmbmvdk.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2ypfsbdhs.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2rvztdhdm.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2mwwhwbic.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2lefnqycb.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2ccewmppj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2uhnynepg.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2zcbwakty.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2answdxxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2wlrrbtgh.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2ghnqwpvt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2vhrucxso.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2dhhvxvok.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2mwhatrvx.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2hstknsfr.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2nirvbgtd.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gt2wbeohlye.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2jmnibepr.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofvcjjww.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2qzvmwodv.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2gyntuahe.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2pgylviyf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2keuuueym.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2wslpasru.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gt2fmyszhhg.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gt2hmydggmm.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gt2namflwdx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2jvatfwxo.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2tvbylabq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2utxlzcxe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2xumddviv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gt2pqxvmvju.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2iarrieak.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2ugwznuko.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gt2falgabrb.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2qqqzxceg.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gt2yzgwrrdm.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2almclriu.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2zawrokqy.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2kgsqqgyz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2nqzkkghl.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2vdwarxbi.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2kkkybtcf.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gt2dbugtmum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2xiajfews.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2htluudwj.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2tsboxoki.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2vgedsygi.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yixldaar.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gt2jhopiaxg.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2ffikdczx.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2actelwxw.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2fjhthjph.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2qcpeewzc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2uobjvwbf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubqbhkqg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2vrtcqjbi.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gt2ifcsmrqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2qrydkfup.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2qzeunktc.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2rckimhlk.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2moqmfpaw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkpkzaia.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2kiunwpme.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqreylib.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2aqspxyuz.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gt2uamtkhdn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2lmgabcdl.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckpwymyk.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2ntnhlsoy.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gt2yulrafgu.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gt2lyylrvrx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2tymicoqr.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2upsankpf.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2jzexdhms.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2mlrsoufw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2gqufjlhn.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2rwhepjoj.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtzmqfvs.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2qnnydrdh.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2vtlrpvop.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2yjrhrrhr.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2hhknqpst.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2almonrta.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2flknppyn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2mtrewfbe.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gt2vazxyzhy.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2xiyhkscr.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2iljffirv.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2atczgroi.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2kjtjkybq.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2blkztbxu.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2zcvrcbdq.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2ouuocgsl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2gckwecum.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2kigorizd.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2ekofrxbk.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gt2hdnzhvjg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gt2crcesalo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2miykydpi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2erklzwqi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2wajjmfyy.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2upgpdgwo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2eltxsxep.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2vnfdtyhi.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2ohkzpphj.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2fxlrdzju.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gt2vlvbwciq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2rtqewcnm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2riwlueiz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2bazvqolx.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gt2axvwwolw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gt2rskvmrwp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2jeywytrw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ivpydlmc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gt2pnujmvyh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gt2wkyhbwjz.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gt2jbjidvqy.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2cazlgitm.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wafwphjy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtniyooo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2mhqdgdjj.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2tdriyrvf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2xwpshhcx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtkxffvn.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2sfvfuhlt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2somzhfnp.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fizfxpxt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2ajaaadog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghgefaat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2wrmudgco.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2feuneufq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2lmcjfovs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2bmhcwler.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2emyzytrf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gt2yumsfvdx.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2vlacbnmx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2fyxoyqsj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2uucjkuhm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2oajjttmg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2aqlgnhhk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2jkiakpao.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2emjwefwq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2uwdatzwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kuosxfgy.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2qrpxngzd.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2ssvcimwb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2fjkiokhi.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqcadauw.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2zyflacuj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2nkmgkrxk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gt2vaeubdar.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2wbpnprhc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2jvggytde.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2pmcdyais.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2ozwhajoo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2yduytomv.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rumxfbpw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czybuxrq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wkeadqde.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gt2bqmjlpgs.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2ojlaymfc.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2atjxjkca.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gt2mecwygko.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2phdcmtyx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2wifebpeq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwhbxthd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2rodgvvdr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrztcgre.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2qurhmare.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gt2iczlpttd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2mrbzravy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2uvaddmen.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2shhgakzu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2tiwfkcth.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2twzybzta.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2hcaogaun.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2jprtgvjb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2wvhjseot.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gt2wrwxfebi.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gt2mrxifsky.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2ihtmzmsz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2gdlcucoj.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrkobaqa.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2oqwtptly.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2gdguvsbf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gt2wpxzkogs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2ofybmlyl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnhzifmh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2tgrtgmey.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2oxltfhak.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqvuhign.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gt2sfsxbkxi.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2dkzwwxdm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gt2ylpgnqum.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2xwoheord.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2cjpvzbir.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gt2rgvnadfv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gt2xtnyjzps.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2azuwplvu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gt2psipulox.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gt2rbpcqqhz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gt2qiraglpa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2lgcmmvis.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2penpubyi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gt2mirzvkft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2ylqnmzyp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gt2yqpkbtav.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gt2pazvcufq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fupaxont.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gt2untahpxr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2aqmnkyvj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epenurxt.html


<!-- 参考信息 -->