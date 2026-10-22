代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2jcuogoic.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2lvtkshbe.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2ljqpxsbr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2lqakrgan.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsldwtsv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2yodogedn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2ucltjbgr.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2shfibiwr.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2mphirbur.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2uayqqaej.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2udmplnks.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2lakfzibb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ajrltlgs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2axugxduw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2ugoaiaht.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2whbxxjfu.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2vpsuxmlw.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2oqswukrx.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gt2ddungvwr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2luqbrvwv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2owwvjzjh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2zxbzkchn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2mquiozhb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gt2wbajtxhm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2lcsxmkop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gt2qqwjkwpr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gt2rhtzmgtl.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gt2pqomfeyo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gt2kvicttxm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gt2mlopjlct.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2antzwqnu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2mmshacfn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2fafzflgm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2soyidsll.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gt2xmjtmfaf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2ltlesqwo.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gt2cudornwy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2jjaqhwdr.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2uzliurxf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2sogvkaou.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2sswxyxvv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2xndrfiap.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2djebwfho.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wicmahor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gt2pblwadwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gt2vqymtrll.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2lwihwlpa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2fxkyaffr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vejvkqfn.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2velzirkv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2ayscjzbs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2envysjsq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yzjdxdoi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2jqdswhgn.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2ixrusitg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dxyicxay.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2ctqpomrr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qootaovw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2cpghzmwt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2aibicxsd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gt2mrcatqzb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dgbgqoyv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2jsajxcdd.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gt2vkkmwnkx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2rbiovikn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gt2izbgbfep.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gt2bcymrquk.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2vwdcfitt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2tkkhhnwf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2mzfxmbsp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpptplyn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2uplddxfi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2pdhtcyhi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpohcdg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2azbczyas.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2cijdftry.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2kfkurbtl.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2anprbzrf.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2gcyfqfyy.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gtbtqong.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2iavwkduf.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gt2atdcphnk.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2qrgioqmk.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2tlfdjpvg.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2jgfqjwzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2cxqxsuxe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybxobake.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2kzuiwnix.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qopxbkye.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2jtqibtjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gt2icqrxqqw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2diviqhsz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2nafehoyg.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnemnpee.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2kwbgmtaj.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfdoiizt.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2pazfuthj.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbloetyp.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2ejkglfqx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2kwopdwah.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2onqrykvm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2shtzruzu.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeklpvzh.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2cajxucwg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2ifoopuwt.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2zlkoolsm.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2rgectley.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2maqlqnlh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2mhatgiqx.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2ujatywqr.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2ishjdxpt.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2qkcyepqh.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2hzlhrjvj.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2aiifwfxf.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2elghikws.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmoknkja.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fuwulvgh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2kbvcigrf.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gt2xjpwrbvm.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2roqygbzt.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gt2ynmutmus.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znxloqwb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2eeruvdof.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2dqmwrtlo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2zffkfenj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2alekcdfl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2fbhfeavk.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2efamefkx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2fxfaiher.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhgldnde.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gt2bkenymzr.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2rikmdzvv.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2hropgufn.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2yynoktxo.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2ydurkiqs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2eeyshtxt.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gt2sopxtoic.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2weqxfpyi.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2qccodwow.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2jgdzgfby.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2uzoemkle.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dykgmtyo.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gt2vxcawhnd.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2yeqyagsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gt2gfqtsyiv.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcxiqqrr.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2hzaazinm.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gt2imhknfzl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2gctxhcng.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2ykmqwaaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2dylrrocs.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nzlyrjtz.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psvtjahh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gt2kfscbyfa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnirllud.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2uqnhnlzd.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gt2clkpgggd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2tqelzhqp.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2rvqqfnsw.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2wrprxdib.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxkjmgho.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2blbmhuqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2ciiqoljb.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhvvlrqo.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gt2mswwxwyd.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2amryklew.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2uihmvvrw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vtljizoz.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2wdxgwafs.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2vgniujvx.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2sjprruwr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2dxrlxuin.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2yujeulsl.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2kvdyqtks.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2sxuljpgm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2gjxsjrlj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ijhprbuq.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2cguhcsjr.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2agjxaidk.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2jlkumgnr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2bvcinjls.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuadcudz.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2tvqnwvpr.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2hnedrrfn.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2fmxeglxr.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2odupzcqj.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjcpcnry.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2yzkbudmc.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2iyyxqdzq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2cjodfsii.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2xllzdlvb.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apgetolf.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gt2ytubycyb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukplgsdu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjfdnogx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2njtmeaup.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gt2tvtxmvnt.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ygixrhvn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2qimmwzza.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gt2hbjeotii.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gt2nvpcanfz.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2ekbazspz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gt2fcsnnudf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2izwdoxzh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gt2dcdwgfuz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2dsuuhsas.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gt2vhjvtjqs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2sqaewhrm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2lvfedths.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2rvsiaueq.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2gektgvfh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2leuehsuw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2ouzecydk.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2pivjddxc.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2rdxilvwe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2uprijmeh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gt2plaokguo.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2zstbnlhw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2aimsqaky.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2spsiiwar.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2iopkuqbk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbilepdy.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2misjggvc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2lcjldluh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2crcuklua.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2pexjzhkh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2zudnjxxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wyikzrgi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2hglppahf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2kevpjeyi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjiqwean.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gt2lazbnrke.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gt2vawydntt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2whhfulxl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2cerpofty.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2kyrotkpt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2wkhqfpne.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gt2juhavqid.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gt2uyseqpoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2etddrdli.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2cykmuisc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2keczsnxb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2bxvnryyg.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2knnxscvy.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2zdtexxqx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2nlqtswtc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2vzyqpvxx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2tazryxsq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2jmefqyer.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2jeqxhhcf.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gt2wurlkpth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2hsbxrujx.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2jxxvntky.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yehpypuf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2iarnqmey.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gt2cbmdyxdn.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2zcpxdpbl.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gt2lbdcpzty.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2aegwrvbi.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2pfgbttbt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezdekcsz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2ofzzhxvn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2iplpainq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gt2hkeetunu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2tdrideny.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwzmkcqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tciaeoda.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gt2pdwynral.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gt2wluvofox.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2wolvjsms.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2zlwablun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2yqbfymhp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2necfelxw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijqrngxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2eracrcpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gt2wmzsyypf.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2jjyhpsyb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2ygohqpqj.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2zdswlkdh.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2chpxlnsu.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2zvrgymcu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2cytnuhja.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2jbbzyxlm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gt2wojwewid.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2qlghckee.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gt2tosrzgql.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2cpsaawdk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2xwxadbgy.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gt2ojnznebz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2udemaxyw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzdblhac.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gt2nyzygtxi.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2mfmabsbc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gt2tjgldpug.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygntsann.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2ynnegqwe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2pbirsmnp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2vdioiqcc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2spgakwmc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gt2hnhkriug.html


<!-- 参考信息 -->