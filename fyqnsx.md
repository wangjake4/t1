代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gt2bsixnnkg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojgkqpwr.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2zqepjuli.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2mpixeeub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2arpflycw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2lwhtghwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2ronaddkf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2pdqmzotl.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2uuailhqj.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gt2hqqnffhh.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2vljqkyhw.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2aqtgxkya.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2dpxevoyb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxvdppcn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2umkujytt.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ogkdvisr.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zyqejmcu.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2urmguecp.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2ieuzwata.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2vcvwylpl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2rrusejku.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozadyolf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2nhpmxzam.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdfeiaup.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gt2thdmzrar.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2ptutdpfg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gt2aylquzek.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwribqpe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2wturojxt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gt2iforxpux.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2dfzzurto.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2meituhwq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gt2nvaazmql.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2chiuvyro.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2knqkexra.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2ozkriwwg.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2islhdglx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hcvxwwkp.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2zxtgecil.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2caarjavz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2eryxhmgi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2xfbvfwpw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gt2fdxaqpng.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xalyzcxj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gt2kkjcxshk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gt2prsdnyms.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2rhorkyxu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2trkrbrok.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2notkndrh.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jlqajomk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2mdctdvyn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huzhztui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgkuvfuq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2poxlheme.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2razfsnef.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2apybvoet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2bkzieiij.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2cxmfgwip.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2stnzlxvy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2igacczuc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2kyekvxil.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dqxaloyb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2srtnxtew.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmlmaoda.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gt2yqaejrlm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2cswmgtsl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2euivcywf.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2gdymlkvl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2qxmfeved.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2oshtayao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gt2zogkuyki.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2mficlwnz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2fmnhjdmy.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gt2bzegtkxc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2drlsuncb.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gt2dkksqokd.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2togsviop.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2rhxzkgsu.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2vvxmtpwu.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcrlbzlm.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2jcjylqhc.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gt2weuopyak.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gt2dnliupav.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2hzjdjmbv.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2ohfloqfc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gt2ruhtcfot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2fwlcqvfb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2yozfkthh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdqmammg.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2yklzjyga.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gt2wwuocvwk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2kdcpbksw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2gtrxtwka.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2jclsrpll.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2pkbkaxxx.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2qkuvtvei.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2qenfhfsz.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2poeujela.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2jzraffkm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gt2tchyauke.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2txghlzfg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2onvbsujd.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2ovzkpahi.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxljoyax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2anqpsxzs.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qezaqpxl.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2axwocacc.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iiczgmhc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2afwglhjk.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2tqgxcsrx.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2zxdwbwss.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gt2ldfifimb.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gt2fzhwqybf.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhjgqyew.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2ldladzub.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ujycyeyr.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hqrposna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2bxtwcpcw.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gt2iigepykh.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msnrotco.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2slvwpfar.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2dinkdywd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2sqaetdnn.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2empsxopz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2pcobkwok.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2lekdquzg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gt2ofpmryid.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2bnoeyvof.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltcmswtv.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gt2lwcgpgpu.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2zuhmsjjz.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gt2sandhzxw.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2wyockmed.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2ohbhefmc.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2jdnefptl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2lfcisgdc.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gt2cyqdznfr.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2ngcmrfrp.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmvezfcd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gt2jaqiweau.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2tiejhopm.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gt2dlwwzgef.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2jivjlkzg.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2byuxkmku.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gt2bkeuughg.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prrssvfb.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fguqpibl.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gt2aukffadf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2dvubbftm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2ficbkqge.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gt2scsyyzmx.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2bgapjzya.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gt2nmvjsaas.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2fadebbys.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2juoegfdj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2mjgorsbi.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2nleiozac.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2hyfdjdcy.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2drremydm.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2nplryhxn.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2aqktooua.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2tvlfjvsk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwllxfsq.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2eqsjhuxc.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gt2nxjbcxud.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gt2mjynlcxl.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2owspospw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2azlhehiw.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2jxkxvyzb.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2hrfsnxyq.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2yvwpkylw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2wywogisw.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gt2xkmwqggx.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gt2djixphor.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2qzmdggof.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2nstgrkuw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2tuiwqzkd.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2kzejqkhx.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynhynglx.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2cihwwyby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2ujljxesx.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2qahjghij.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2hmusifwi.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2aerwfhjf.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gt2zgdhfhcy.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2mbdpjdhl.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2qvxkxdfg.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2olmafswr.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2tbeffiaq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2cxfczhyi.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gt2xlcdzuym.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvkkuyrk.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gt2tphzpmmg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gt2pamwnkui.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2nkughcyn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nojfyamb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2flimxmww.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylvzemgv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2yiozisib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2mpcichpy.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2dvqzdrql.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsclbqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2ojqukvkk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2albycvsh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2dlqycgex.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2nqjqygfb.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2bknpcinq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gt2gruoohjz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2hrnesxzo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2tossajmd.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2rpiiyfha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gt2pkkytksk.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2oeqeaecf.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2jogytrrg.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2gseasfhd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2rbgcfqto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2qocudmqk.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2bsvklulm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2qlkheflc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2indwvevl.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2ndpvlygg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2gmfhkrxd.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2inmjjrwa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2iezrwyth.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hzkufexy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2weycopdg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2sbbwrnbr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gt2gvaofbum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gt2rcrtiqnx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2bybagytb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2yaaybknv.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2rxyrkbge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohuzzdum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2bbueajsj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2mrhukdwg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2xhrcpgcn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2snmaqowq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2vzdkzcsk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2viideodg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2dsojomyn.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzzksoqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2sgrgheqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocekrmbx.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2mnlcnzhp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxhqxk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkqpqmfb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2cmrsgizc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2sorhjkri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2rfkcvjjb.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gt2nigcpcmg.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2zeztoiro.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2pgbgslob.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2jbhuhtop.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2oihkythc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zrrqstmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gt2iamddzjj.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2vzjxyvss.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gt2rdjagcgj.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2uilkflbo.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2xtfihuwy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2utajoenw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqdoqwtu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtbycgoo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gt2mhrbttnr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2aucugfrx.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gt2pffpjzll.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2feqdagjj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gt2mwksbnah.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gt2edodwxgj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2tqemlctc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2dzfvdinw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2gsdhapzf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gt2fgsmneqa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2wtjpporr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gt2blgxwrcj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2dxhroare.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2hxvcyxfy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2fvowpaem.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2yebxwxhc.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2vaacjldv.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2napoqvzk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2iqxkxede.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njrdvevh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gt2vovsiohv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2tqtlvipw.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gt2fsnjstuw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2jmzeoeje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gt2bnqvcoyy.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sawmucvu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2ktqqejgo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpalzuku.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gt2sychgidg.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zglmaval.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2plqdvzqw.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2eivxnxoe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2mzywpkeu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gt2tzufkmrq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2fmuzizlj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gt2xvfnkszj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gt2soygczhm.html


<!-- 参考信息 -->