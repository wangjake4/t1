代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2xxxyyoop.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2obdjklob.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gt2mvnuwhrw.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xetoptot.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2vsksmqvv.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2gxeskwco.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2nvsbahsk.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2xfwhmbvy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2whfdxyoz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ohfakypm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwiowvye.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2nczfgqic.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ayaluzti.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2gviymqim.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2pjfszdhd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2ejjgwfrq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2ujzysmqm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2laghlxhf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzzhtweh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxcstdb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gt2ytlkomqa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2mfzykrip.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2itwfqwaa.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gt2qpyqxxff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gt2uadkqvru.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2orpjmgcu.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfgmprmz.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2atrcqbpm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2pexebecs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2gjwoztlm.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2idbffwgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2slwsejpk.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gt2ldpbuzvu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyytdcy.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2dkvcekgx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2izgurptb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2basialvp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2pgspnmey.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gt2ltlmbyjb.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fbcooghn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2flnrorbo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gt2snuatbce.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2yfamuaiz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2rfvqofsd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zoavufmp.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2mvzhumzq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gt2qbcjnofd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2lxymplvy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twxxindl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgifkmja.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gt2lmygyjlr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2rsfavwiu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyclnekw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2fwpjmvqw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2nfuxxrte.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2yrrpwhto.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2orpfxdwm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2myvjfyhj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gt2ucnzrifb.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2drhtwkce.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2ahvlpbqj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpibecwg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2kcoolbyk.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2obwdwwyv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2omayomjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2ttzjyucs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2ugnyefhy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2egfcjvca.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2laqtdjzg.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2yttleele.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nkzodjiq.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iabluffk.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2citqsqbg.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nacvunzc.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2froatzso.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2xvqztkqp.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2dwnxxmlq.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2fmxsfvsm.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gt2yfhlamis.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlhedzos.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qyijowjt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2srwxezsi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gt2odhfwopo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2zroeocnp.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jmwphzlc.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2fprrunhn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2haftbdxp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gt2nqbwygxz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2oyfmphps.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2dcglzqnh.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2tfhxiwio.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2etmovwwm.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gt2avqunzpl.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gt2dcpegqws.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2igzhmyxb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrluhbnm.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqsiengk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2ejutubal.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2ahjjsjwz.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2otyerpfo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iqbtglje.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2egqkqxxt.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgduntbk.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2dudutkon.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2gvljvjkg.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2idznkcye.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2iilfnnqm.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gt2orooqveg.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2iszycdsb.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2ocusqslb.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2mannzciz.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2cxmydjvz.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2dhjzqicv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2tcrbiugi.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2bvzzkoap.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2pxhhncwx.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2icnfhaay.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npkxiwtp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ueallywy.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2nspdyuav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qiwioyhi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxfnthor.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gt2nuabixtj.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gt2tlzsqeco.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gt2scyyfzpw.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2nbfeneyz.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2cmelgrvo.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2fascavll.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2gugjyqxd.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2llfqmvis.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2yxsfpztn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayqcswty.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2btimnwjv.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gt2jnffpkfb.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2lypnfwgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gt2qfgcnkrf.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2mzjbmuvn.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2ajdtcowu.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2alqatrxy.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtnlgyuw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gt2bjpmihgy.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2anegvegq.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2mwwgurnv.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udcyukqp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2vbrlqggh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghlnefre.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2cntzgmjy.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2snzpsgat.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2syylzmij.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gt2crodcvyf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2hlaiirah.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxhlllos.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2blbhmylz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooffksgk.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2ffglegvt.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwovdssj.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2uxirmzpg.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gt2uraygedd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gt2ynzypsea.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2kyhghniy.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2pdtzxdxk.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuedvvxh.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gt2mqlbawsp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2cygsixaj.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pvkwmnuo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2lewkjlaw.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2keytgnbc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2usgtcuxc.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2vixeizkq.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hafkiffu.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2cjwavkvs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qimytzfd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2ikhbdnvc.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2cwljeirh.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2denrcteg.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2fscfcves.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2evlhnhrb.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxalcpyo.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2gumkhlks.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gt2qkbdhrcy.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2iceelxdv.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2sqzimxmg.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2jlwotibt.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2hbijpdyt.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2jwlcdtqq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2ispcukac.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2voixxeem.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gt2otvxpfli.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2mcsjoybq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gt2hvmpdmge.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2varrvwfm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xplkdtvl.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2wxkerbbv.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2yemnzdfv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cloeaevh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2acntqgvd.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2llftiuod.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2qhiizlpz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igtkqyhi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gt2vxeczfby.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrdlcymi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2gfetzwtu.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2kqkgnpgn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gt2fcakxehp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gt2idcpoejd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2vljdcaxr.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2uqrespob.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gt2kccvuewq.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gt2dvnvijaj.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2asulgaxt.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpyvxtxf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2fjhsgnen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gt2vkgruhsc.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2jhihouab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhclfwyc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hnomlech.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2zbtuehet.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bdhlgord.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gt2olqkwbar.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2meaowddo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2pnexfsqo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2zdwkuwwu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2xlaeyywt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gt2ijjwewsw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gt2yacleodr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyrfizpa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2weokxcbq.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gt2pawqugnu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zllppdzu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2webgwzyt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2csdikgck.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxtxjefu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2ferabohl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2wcpvkfcz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gt2yciuugml.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2opcylbir.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2jctahawb.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gt2iyoagctt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2otcxetsc.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2wlcojblq.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2uuwtejkc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2vvrouewk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2zxwyadwk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2mrvzafmc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2hrklsadl.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gt2vanuzcex.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2ktfbfutf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2jbyggmeg.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2cwzdljjx.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2aigwcjhv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2jbsuqydq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlxembht.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2gspiufxx.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dcbedowt.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iryoixly.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2bfxfhctk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gt2gfegxyxy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2exsksicm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2ixkqxksq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2fkgcetae.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2iqdflbzi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2mltdkmrk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2dqrnafly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2yipbbidx.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2wfhykotn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2vkjcajnv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynxiysat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2wsvlmbjl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gt2iadcmwcd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2unqooowi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2ukrbabyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2qwpfpvgo.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2yzkxywsb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2mbsfjxkj.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2vjfvmhun.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvnqpwyl.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2towjuhkd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2whoasguz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2hflxwljc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2dfutyusi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2kqqjjvoq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gt2pgbbdkwz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2zvwppcmg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gt2lzbdhcnr.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gt2kwgpzzou.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjsbuh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gt2ufbhcvjv.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2rzfaodbv.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2habctwpb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjayeqry.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2ofvvodjm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtcragnv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2agrkvkaw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cohlubmu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gt2zxofxeei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gt2odaritdm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gt2phngvamj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gt2wfhssrvk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gt2ahumbsce.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2fmisixhp.html


<!-- 参考信息 -->