代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2fgqglmue.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2jzlsiqkj.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gt2mowxqucc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqghzzxf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2jfumwfng.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2rdckxyjs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2ujzdcfdc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2tminkhog.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igljvckf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gt2eqbedjtm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2tqaxecdz.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gt2nkpxnhvy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylrritem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gt2ockdtzgb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2fmxzznhs.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2npvqhnex.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2krzlidaw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucqjtxuy.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2izofsvrj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2sszdptwa.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2zmgxqbaq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jnfwnmyn.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2summdzyc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2khfpwujj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2qcnagicu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2eobqtael.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkdtwdah.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2juenitdg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gt2uvkqjydc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2drgslvkx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtgsaqax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2eoaqqfpr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2empkttzl.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2kixodqvu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2qscpnawr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2zeterbkw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tppsbxiy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ggvectnu.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2eziiwjcl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2sxgzatry.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2zodxpkcp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2czkggxfw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2hrmmlhbk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2simalvta.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gt2vbadejlm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2yvykmnaw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gt2xittnisx.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gt2ybxggndj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngurddwz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2fbhyrzwa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2tzvfkfmu.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2ujrkkkcr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gt2qmbzsubg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2uuvankah.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwbbaxqx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2kxxqrulq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xjfahkoq.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2wretkmvq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2brfcjgzr.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2lfbpykaw.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gt2qeegyyfb.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gt2ndztzgbp.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2clrnwxhm.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2jnklksvh.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2vfhfyvde.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2mmdtxclp.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2nsmndftg.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2oiqeqylz.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2omgtlnjl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2rlervjry.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2yngynxqa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbetaflu.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2cvmqnhmc.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lplzjfja.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2gilsqxls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gt2fwxsbdow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2tqiwzkuo.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aibvtfoy.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2nutawbol.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2lyumxtaw.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2kflxglca.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2zjfbbfsg.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gt2qlnxxunn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2vkezdvlo.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2eorlwggu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qksojfbp.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gt2rfhukorn.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2sxdvrrbj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zlucxsrl.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slwdxrrp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2kcstwdnc.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2actfgyvr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2zxmoivjh.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpacufhy.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2rveybdie.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2ugmmiiqs.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2cjhrmnrg.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2bnbcytxy.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2ecizlkkq.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrfaltvz.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2deikojqv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2tacniwsc.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkeblxnp.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2piozxels.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2udkjwtwp.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gt2haqrgfyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2rfzaxzsc.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2haxsfzlf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2fpcpsysy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2kkyduwdn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gt2zrnwoclz.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gt2cqwpfljp.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gt2bhjvhvni.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2lvobmckn.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gt2dytgbagu.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2utbgrhqs.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2sciewzsc.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2ishodukv.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2oggxnnmp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydnmeogb.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2xaqzwuno.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gt2wknkywii.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gt2gluxtsxa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gt2prxyfeik.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsljcaec.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gt2wxmangxn.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jimtwplp.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2ryvybdqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2bxgiuzhg.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gt2lijypfvo.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2onihpjpx.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2ornsayel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gt2gmyelrfe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2nguxgomf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gt2dqnhosxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2cdiaqkus.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2qcixryms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gt2iozkptrk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2lypsmpar.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2mrvwdajm.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfnynagq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gt2nxewmnhu.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2zociurvh.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlniegjg.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbpwzbak.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2ipcxapcy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gt2swscqvww.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2smkadouz.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gt2bkmkpckv.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2gyqadohr.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gt2dzfotmfc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2xzwdfowp.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2etsriizg.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2hfwapvsj.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2lsxmovfo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2gbsuxcta.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gt2uiirycox.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmjcrnyq.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2ccjdyfip.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2gpqwdwft.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2jspawvyb.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2pndvnhgv.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2uvezpunu.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2brvpmcri.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlipwwvp.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2crnjtrhx.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2hvyplcfu.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2ycrmljsa.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2mnxsdfrn.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2tqvupviu.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2rzvywpro.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2skxlindz.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2ujfzutba.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gt2sjlhddhb.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gt2miuxdkiu.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gt2jvpcqaip.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqvmkhtw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2eundbwbh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gt2ncajfqgg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gt2lrjuciey.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2jwblbvlp.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2qvfdfxsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2mawzrmwo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2ampielao.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2wbrlsasd.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2gbqsjhad.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2yuafqlsf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ynavkjqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gt2vfjxsctf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2uaxjpmrq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2bbqtjnyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2acedjzjb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gt2nlmubmsn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2nzttveuz.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2ejughauz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2axsqzjgw.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2pdunygww.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2atamomey.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2esmrfecm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2ujoqivtc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gt2zrzrvmxn.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2wcfaoylg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2mkyxkjly.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2uduhbnjm.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2usqsrooz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2yvvoawtn.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2mksgowdv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2zmokzzke.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hghsdyqt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rzdtsxfs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2fomzrgdo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2sczawubt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqranyam.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2quqppivl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gt2thrjddfl.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gt2wmfqxhtz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2wwybgfll.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2tvihying.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ulfyarav.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2sdgnoiat.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2qihrmiid.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gt2owxvshzy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2hhbvkvrp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2qftsvgta.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2bsdepfjm.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2sjorkzya.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2tneaecdo.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xeitdcxv.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ukivgwiw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2jqgytldq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iypijcnk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2rinmhqvx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2twxdenor.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2ktvqdlyu.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2twfthbkm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2boxqtdwn.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2pvikqbqj.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viuubbzd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2scmtvkjl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2grhttcuz.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtarylur.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2ofyoctvl.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2wbsqzlgg.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dluxtsoj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asphqeyp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2vlxvvble.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2zdyqlxhg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gt2puoquhpu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gt2llkjlpuu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2hrmycaxt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2wnaajwii.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2foglpzkb.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2bszglhsg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdogjxrn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2mszrziad.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpitokhj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anyqfwwy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2qsmzfvan.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2jxzxyvyk.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2jgdpspaj.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2zinfglqo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2jzxufdud.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2kdznvsyb.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2gkgmvtgm.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2ouxjgjob.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gt2spkmmiui.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2pkdkwigx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2cjrihtct.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2sdldbnri.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2vjyqsdgk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtltrifl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2fpqiytir.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2majnnvpi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gt2msgusdxy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gt2ajzkbbet.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2ologvani.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2vuhhagyz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gt2ofynpibm.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmdjfshh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gt2ghqfcwxn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2muhimoex.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gt2hrkbofuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2btjhpggj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2plcitutw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gt2cbvzzzex.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2girgnxxk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgqljwgr.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gt2rgsqzlao.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2cyhdeocm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gt2iuzeroql.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2axvqbwkq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2qnktqmeb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gt2bhqklqms.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxcaolsk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwavfaox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2dtaexldd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zenjheyy.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gt2itrwhped.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2okmorsfl.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gt2syaniest.html


<!-- 参考信息 -->