代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ilmsvqul.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2eiqiioke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2sodvpwrw.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cpkxpywe.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2occhmdbb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2szhxycbs.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2xpdrylen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2drepynxh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2aarwcitc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2ysfaggfz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2edsoffrr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gt2pshlkxig.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2sxpasmjh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2ldmwlfod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2jutougcj.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2huphajzf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gt2rkzkpkzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gt2mtmgfmsa.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2dyyracad.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2ciomexha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2wobrrmug.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2algvynjg.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2oqiqzaaa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gt2vrmljolf.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2tpnjysvk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2zufnonvv.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2cubfxlwd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2amipemwq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tomzrgld.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2wgviucuv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gt2bawntzcv.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2fjfpinug.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gt2psozmfyv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gt2aarzdhdz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2jqbhbicv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2oaohqukh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2oynhlvyu.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2sbsvvzld.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2ytmuewuz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2yoazusxw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2hbbehuyf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2izlfdima.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gt2xswfmdqt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqfgqffg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2borwlhkj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2smubxjne.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2qhwphgeb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2ueqkzcks.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2rsstjbdq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohpjzpxi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2favunfmn.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2vnsgiats.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gt2nxhdocvw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2nsxzhybr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2mirwmrwh.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2aavsdjex.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gt2hwskgeaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2dxliwzob.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhcisymk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gt2izjhxftx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkmvbjgt.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gt2pigaviqh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mzyhhboe.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gt2nskypppd.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2hvctbzdv.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2ljyjwtlz.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2sxqxvopo.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2pohjmczq.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jyfpzyhm.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2uilhjsck.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2mlbucged.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2bqjdnncv.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nasxwcqa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2fibsbwfk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gt2htlteigr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bztxqkrd.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2inuaoihf.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2hklafoib.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2ywctevjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2gkgkynxq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2srwddkoo.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2mcdnxwja.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2cwpxtxmq.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2ztiffrur.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2fylobxqv.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2nyyqjwjg.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2nldtfden.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2yzjwnsep.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2gwfjyovf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgakroap.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gt2xmgtgqsr.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2qnimzaga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2zomyrwxu.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpvnldal.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jqphnzdw.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2itflkfzv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2qcufqpgl.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2vwlqvpoq.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2ipjpcbig.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2damqmakj.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2awawjrpa.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2bihzcsfq.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2guuqzbia.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2sjebvxcz.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2pwrqkehl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gt2ktkbzhpn.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2bmeepjxt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxrijsm.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gt2bywabfgk.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2raogbbfs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2yogkidji.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2ioxdfipj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2fmxsrxrh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2sqlqanbf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2hppcclnn.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2ziymychm.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2zqepcgiu.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2uepvhfsh.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2abqfrmsd.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhthfazg.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2zoxwgzpc.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxotnobl.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2iassbieq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvgrvrvc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbdpqmf.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2fgrtsenj.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gt2ghptsbkd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gt2emdfvpqe.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gt2wjnhcdqu.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2esdnreir.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2oqbpjsbr.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2vcwffjht.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2vbegyaur.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2xibwutgc.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2shglhbxu.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2qhkjzsbw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmsjtgyt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2otmadfza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhcetfyd.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2uhffasxj.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2slygmgly.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gt2gcczvgbr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2kbmieenw.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2hpuvgagq.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2owsrqkex.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2obmjmxok.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2lezhylwa.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2uwwkooqm.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2yeesrcvt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2guukgerc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2ihbtlpvt.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2blhkyuux.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqkxzbzc.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2vkeqoulm.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcuavbqi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2hnlpwlzh.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lrhjstcn.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2sqnrphnl.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2zengkzzj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mucrfyvb.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gt2uddjzprs.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edkreseh.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gt2gyffshkh.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2ytgzkbbd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2iqyurvjf.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2nbvivosu.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ybogfnua.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2ahgviwjo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2jybsjnbs.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2cxabdpyg.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2qhcpllnk.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2protdjpi.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2nxbpyebf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsdnnny.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2anycibjz.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebhikaes.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2bedkyzhd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2lttugclj.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2jgkuefjr.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2ebehxklq.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2iajeiuin.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrwzoofa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2cqrahnev.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gt2dvqffeoy.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2ginxpevk.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gt2wxxxvsqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2bwdqjbxp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2gmdrlaml.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gt2vtzbdacs.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gt2ylilrxpb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2nxhmqlas.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2zdsqlvzo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2fgclrljf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2tkhvtvvd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gt2nxghijfm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gt2nefgagoh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2cybrpvmj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2hwcnuvhf.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gt2yunmikec.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2gnnixobj.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2tgxgpqpl.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjqzaqzh.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2yiosjbit.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2zkorwuqo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2tsetzaes.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2pwofggos.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2xzfskswe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2emhlrlnb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxddgo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zdohnfhz.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2yvkdqzpu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gt2hqnujycj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2raivrsfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2fbrhgdjz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2scsoxhcs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2sdxibufx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2qzxwyter.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcmzqvho.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2ttiuacka.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyvmqine.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gt2slpkqrnc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zborfwqq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2flvkddfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2ndjdlbwf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2ezumccbo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2mvvbgxgy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2ovzpxyss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgqlikgx.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2ufplvsqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2ynismqje.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2sukeplkp.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2rzwzknfk.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2gyjopkdl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2fdvomkai.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2opjdgmef.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2elircgto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2hygjamkc.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2qopynagr.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2lmheevde.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nxxjacke.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2wmjqbtgg.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2ykqffyzs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2xyfmedmy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gt2mebqucko.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gt2bicnahxi.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2srqqqlxm.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gt2wlyzeklb.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2rqoyclcc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2wvnlxsec.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eattxjkb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2awwxycnc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pcczjjuv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2hjwrgana.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2eyoghqrg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2cdfivbau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2cyyqwnqd.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gt2tbofuxst.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2trocpuxs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2oqsjqnes.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2ypmklyvp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gt2jfbootrz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2xfxisfkf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2gvpgvyqj.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2rtehgudb.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gt2zzphhcah.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gt2nwuiznwk.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2pwxqralx.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2nzcuvkyq.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2yujlmkbq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gt2qhahukbx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gt2bvpbzoir.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2qnxeiudt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2qboucjao.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2aytxmtei.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2gvctesgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2puumxavd.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2ruwmwouo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gt2gsqjlisv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gt2fwrrmrdb.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2gmvoxfys.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2djsyixzn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2xodwirec.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gt2clidvicd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gt2klseaigw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2jdtelmxi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2mjjuriyr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2wcvpnguf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gt2muvxzgsh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gt2vcfhppuk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2oeabwwkb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2wdoxflqd.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2zbgmeljl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulrerqkh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2xlytkqxc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2ukgdmvjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2zsnepbvo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbxxfkjh.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gt2fzgzojee.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2eymfjdox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbzyobqo.html


<!-- 参考信息 -->