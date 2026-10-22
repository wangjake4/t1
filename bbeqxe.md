代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2qunmhfpb.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2jbocckzq.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2sojftfgs.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2wcpxxepk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2qeprxkji.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2oohtbwwd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2fbpocidf.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2lackpqdw.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzmtrnkd.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2uwlqiuio.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gt2wgvrqsrq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2dftviour.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gt2yvbhdrmb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2vwybzugu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2dapathei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxxuaepp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2hjggpump.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gt2oszpkavi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2pkxsceuy.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gt2lbavpaaa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gt2iomjybge.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqjrexie.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2opgtbksa.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2adokqbro.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygyulbyy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2bgifrcvv.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2hazszftt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2azvzmerh.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2ntasmlel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wpmmxvdx.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2zkbfjlgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2frlnbctg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2eueinxul.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2jooumklv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2sycltynp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrpkawi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gt2srsiuaog.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2mbdhbrwf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2hqtowwuy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2iydtjxcm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2xuzdcemp.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2dkgtfnnj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2xaxbvsjo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2mdcnuwoq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2paptiqpq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2yngqwrja.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2oviyhszh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2kgugrzcc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ibpvoxlz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vndchrot.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2odpxgdyk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ciagfgvp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2tqazzdke.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2kusdqqpe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2exrrtufp.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2xeknxvmu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gt2vqcimuiu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2jhvofeiq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gt2vytugnzf.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gt2ezgcbuwo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2jsspjnqt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gt2libvxjnl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gt2jxqgrqqv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2htcneeea.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fphlxhzt.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2hokjaaxo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iikebzsa.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2onnnimlm.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpyyazyd.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2vgttlbxg.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xratukje.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2usktsykd.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2ipdptuot.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gt2onvyzvjm.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2bokwvrhf.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2hrhsbcye.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxxmirop.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2zmzppwdp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2qyyuzmdk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mabizimj.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gt2vcwxjtjs.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2hibcqnsw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gt2zesfgyzk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2jzegofnc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2hitbwuud.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gt2mzaokovi.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2txgjxain.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2zrandnzv.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2frlrujzv.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2gqveewno.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkpyalz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2afzzhppm.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2blpsjwto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2gpbzysvq.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tspqwuep.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2rmwznbmf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2sdzkaixv.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2akkgclmx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2cvzlghzx.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2kslnvjon.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2wkeistcc.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2xuzxedhc.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2wqljheyc.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2rzljgfjm.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2clbscklw.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nhnqbdwc.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pnxlpfds.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmvladbd.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2zbsmfsrb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2eqkbybpx.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2lxvcoqru.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bfezdrul.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2lmgtbnrh.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gt2ckuzxnys.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2czlbhrpv.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2hgfnhxhu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cakuwbht.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2pfbhtgtj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2cjtvejyb.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2nenzwkdd.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqxvlpwt.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gt2mkvcnzup.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2yktkezkt.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2cjfkaevb.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2cdqdspri.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzwcqhcv.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2jmnxhmqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2xaykhvkc.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjbdmgcr.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2euphapvq.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2qazlmdql.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gt2bbdjkpch.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2cudhlrkt.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2diaccdas.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2rmmkqamj.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2kdzauddk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gt2sjxcwuue.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2shzdfnbk.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gt2owrhfwdd.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxrqvwii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2dubxbbws.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2kdlxzyxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhmamlco.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2hdcqhxpi.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2fktvxdxy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2clmtwkwd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2nylzgzmo.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2rnvfciqf.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gt2izhvwulj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gt2dwcadoay.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2rliakmxr.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gt2boeevura.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2lddrckad.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2igkqwwob.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2gywztnfk.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2wqylxuku.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2jxahlfjs.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gt2kmdajztw.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2pwtmflln.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2yplxersn.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xonljblf.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2kmjeaxmr.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2lagzphrj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2jnpnmlba.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gt2nvqgqxfi.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gt2cgnrfuhb.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smqfthjs.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2tfvnlmnj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2trlqncmc.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpffmcoz.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2oydfjaba.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jvlofgnu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2jdnarhfz.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2qrpdwkqt.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2hynlrvud.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2vridhrug.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2kqywcsok.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2daauimbf.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2ulhqhdkr.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2embqnovs.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2ctatbvzv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpphiab.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2rftfccbv.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2vdwocuiw.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2exbqndsv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2wzcqtphg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2uqfombmn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2dlcwcdhc.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2afdvdwbf.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lixbfktx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2xoujojow.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2ymlmqyos.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gt2lazsxmix.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2gsirnlsb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2uvxekojp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cxtlpghz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2nzdouary.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2ahbmxgxo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gt2vassfiom.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krrgxkse.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2rwamfotp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2uuugidlm.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gt2cfxocnct.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gt2zkxwmhgr.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2lhtevanw.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2nqaolrzp.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2lndnytyo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2rsropavw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gt2phxpcadn.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gt2swzpxyxj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2clumdkvs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2znfpwcrp.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2tpviatry.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2srqyqjgh.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2bjvcogkr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2vqaiznzf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tgmyecby.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2fbdybglk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2lpuqnuzk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gt2cksotebb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gt2vqndlisn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2imwjmxip.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gt2uvsmbkjr.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gt2vlefsgml.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2elvbkhke.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkpewrmf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2rpruqplw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kenfboxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2vklaezlz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2pupvnuvt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2spmerbqy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2ovlnmykc.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2ddkustwg.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gt2jlfwggok.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pffiviyx.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2gpucdkyi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oftsrbev.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2rioiztwu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2gcgnmgkw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2lkotaitu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2ymdddzdm.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsbtyggl.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2npjpfvhp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2xxvalcls.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2zzexfsrr.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2dwzqxkxs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2ozxemwbg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gt2nrwrtdia.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2jopegjjz.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2ptxgyrpi.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2cddmugka.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2pkzrlold.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gt2cyxqyjcp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2jvwgpesq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2znztuotr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgzgjhu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2gymwrcyh.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2icavgujf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gt2nldnskbq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2wvponwrs.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gt2gzohoxql.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2wxzfszat.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyprbvvj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2uywmusuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gt2pqkbtcvy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gt2dqojmqva.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gt2rwzsznxd.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2dtaypllp.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gt2odmbooha.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2qftqejmo.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gt2dqbedpvq.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2vwthxbth.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2veofmghr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2pntguxyr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2pguagtmh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2abbbknzp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2uhiqhcrh.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gt2uvpxdjjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gt2umtgxtxg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2yuuiihiy.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2cqzyknil.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gt2lwmpuhku.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2cmelkubn.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2qjcljwgv.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gt2fynieoxt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gt2yaynakmx.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gt2efvftnni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsdhbasu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2ebckxdvy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gt2tghkngml.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2gatqvalv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2dhrnjmxp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gt2kaylzupr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2kqbcgiai.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gt2iovgzhqp.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gt2kebxzeyx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gt2jmrrqdrj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2xjqzqdyx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2ratlqicu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2dnrsqfon.html


<!-- 参考信息 -->