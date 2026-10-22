代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ybajsvvi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwwdhsej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2dphoyjot.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ywzbuhql.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ftrcumki.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsmykhzh.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2clvriita.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wjcnutsa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2lunpkryx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nzfeagvm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2peqdskjw.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msyteqfe.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2vchclurs.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2szayolko.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gt2qkxvjkhj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2ycpqvhcm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gt2xltjxvrz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2evwjehgz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2znhhaqse.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gt2qzkpdvgr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztyhrhrd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2sxdrhskt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gt2atoxatje.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gt2icryoelz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2dpkdjclg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2nzyjsshx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2xzlwgmrv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2jexuqlia.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2susjkwje.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2turwbgmi.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2uquszjzs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gt2gzouinlq.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2njgkbnfa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2zpiwaral.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2khkqwsac.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2amobmnnm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gt2fzaugden.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2pvceahgd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2xvtdxzpk.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2cumoxqsf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2nykevmuw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gt2vzpkyaku.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2fymehyzd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2rtdbvynv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ctifhwdw.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2qszncivy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gt2nepbecfe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lprfhsdc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fkliqlil.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2aomzwvzw.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gt2klyhggfg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2cemmioxp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2ddngrggm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2gntgzrsh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fzuhpmcg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2ckiasahe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhznadeb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2tdthloij.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2wlzpsvgm.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeuqyalc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcnpniru.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2pfzotetf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gt2ctkxaxtk.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2vxqmnvec.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2nwdrgido.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gt2hdffwkro.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gt2oipavrtk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2xwuaztvu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2trekuyen.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2iauapdiv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jgsuxlej.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiozuors.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2nwwirykg.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2bkiutjne.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpetmsac.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzwjhayl.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pcirsvhm.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2unkqiglz.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2ouixcrwg.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2bfkjjiqs.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujhbysqh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjkanqdp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gt2qgsxjgwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2kabrsiwk.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gt2vsflfxtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2gjmviipb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2xtmsrzai.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gt2beseffvs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2sjwokxya.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gt2wzqhajkc.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2vhiugjwh.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2krgegjna.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2idsenhcj.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2kandcopx.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvhaseyl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gt2aidcpsvf.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2ijsskqfb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gt2opzstpge.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmzudeqa.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yygkfrmb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2hwrzqtik.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2atflllrp.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2jrrutsvb.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2luexgtxi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dipjxdpt.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2tptratgv.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmjkhbzo.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2dqiyabwu.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2ocbzqlbm.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vcxvwmju.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzbbtuwr.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ilkacssh.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2efswkirw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqteldmg.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2xujpvuev.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2btncflju.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2iliduhxl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2kiukgbci.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jvhyxgim.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2qgcjfxgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2mfdrxsgo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2vmpadtzq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jegfpqnh.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gt2ntrnxneq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2sitbwpnq.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gt2shvztlxz.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvssbhdv.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxxpqvat.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2ctjwlmzq.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2szwduygu.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2ortgnzht.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2mxyqlceq.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2sqqsjpzn.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2vsqndqpz.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkupkkkw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2fdwgubzk.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2snmkyvzi.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2plptvzew.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2vfmgdlom.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2bztruoan.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gt2uuyhzqaq.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2ljvpzoxa.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gt2hiewyegz.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2yawplihg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gt2djqvzbts.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gt2xlsnupha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gt2tqfytwce.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gt2kretvziq.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2tcrvidtl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2cnekipkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ikcwpfwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2nytttuch.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2vmdtcrge.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krmqbmlx.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2haerpzlt.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2luaybxry.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2bvqfvjsw.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gt2hqagmfyp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2tshefaqq.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2xjjnruyw.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gt2ccfgxxiz.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gt2jmcfdzgu.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gt2iemcwnyk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2srxhhulx.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2djdjbjiq.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2alhcdykz.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dvtahrwr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2jmalccks.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2mgqiuixx.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gt2ogpsilab.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2grnujcpo.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2mumyjqdv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vghgqamn.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urniiilp.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2xentpoqr.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2lxodtslt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2weprjchl.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2lxahdhed.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2lbmbjwyy.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2faohvwyf.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gt2kcocncxf.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2byjulscx.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2nyetbqsf.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2rwtmwcqh.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2ekoqlzkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gt2wjwzzbjf.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gt2rsybwpqq.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnzstdkq.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2ptmyfpko.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2uuzyijbe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2lvzfhmiz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruigrmsu.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2atpfsydb.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbxbabap.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2zidbebdo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2xpsickzi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsfyualp.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljuyolga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyebqwhm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rvccaxlr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gt2etumzapg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2unmdrkpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gt2nlgacfkc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2bbpfxguk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2ftsidipu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2wgizkyjw.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpcznxhf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gt2nafzjtau.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gt2ukencwqh.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2lfswcxcm.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2eeifbvzg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzydwwbu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gt2ejawxnpc.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2babffclo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2oggkvrdg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzbhbtfr.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2yqdumqzf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2zfmpblcv.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2zrtqojpb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uasdkzxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ykqjyndo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2spqsraaa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2xoigpgad.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2mgqxtbyg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2zjzlkifh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2rydicvkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2hcdzjslf.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gt2letyuals.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gt2eixrdola.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2vtjaezdf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2odfdbmsq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wgzrcncn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rugvygox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2dqendjzd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2kfywwwsy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nalwfirl.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrafjytr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcgriko.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2cufrpvxw.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2xkmicfrd.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgcjskdz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2ilmoycxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gt2jyjbhcmb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gt2xamggngy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2lxfqoikz.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gt2bgdkqyqa.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2qirsegev.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2zmdqydgn.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2gyzwjmjt.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2qzcjtopc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2wtevgnds.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gt2alxodimg.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2khrezwau.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gt2iygwkjlz.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2ifzrmtgd.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2jvijyflt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gt2alkcrtbb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2otrftbzy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2xitvagwn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jbusaepv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gt2oupteuey.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2pzlkvboy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2kcpinlnz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gt2jctwdhiv.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2mqysdpwk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2gbkixiio.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2phwqzjaf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvdppnxt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2pfpvhfgs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2rejvbova.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2xlccrdta.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2wkarxcxa.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gt2vxgszupx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2fwnnrxaj.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrmivfij.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2htdnbnjk.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2yhvwtdnh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2xoraiqrm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2vvtgoomv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2ogmdfgfp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2fcqhnwmk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gt2ytzobpta.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gt2ojzzihrg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gt2nonjszuw.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gt2cgwpylfg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2dybwydiu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2bihhnsnl.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2gsxucehr.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2jbcotnpn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2jfleyefu.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqalhdfy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gt2ujfuxqhb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gt2ybnwende.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gt2zhozbktc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2etpuroip.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gt2blnkiqwk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gt2brucyrjf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2uusjsuid.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2orlcrusc.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gt2gcsvtrnn.html


<!-- 参考信息 -->