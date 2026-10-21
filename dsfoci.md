代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzoigfie.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtdullvttz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtpjdzthvd.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gthuwamtno.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtuegmxnss.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxcggdbw.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzrazgdqq.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtoqhtjtqc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtollcgwyl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwomzpnnf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtnqzfmzgo.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxymcvbl.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtujhagamf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtdtnazitj.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtfjrdonsb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtfspgsnqq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtrzvyhtfg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtehmmwsfw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtbkpqeiid.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtlmhznyxn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtkjoukpji.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtxzkxxzft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxahcqbsy.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtglgovucu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtjcuwzram.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzgfuywsn.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtwyaqayve.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtceqesgco.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtvvttspay.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtmazltnsy.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtfogrzvoo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtmwvgfhug.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gtvvdjagua.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtadbezfjl.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwipantl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjnfavou.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtnujfczcx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtpbhpooij.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtatgdhhdw.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvbvqxmqm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtjybfsqfx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gthsaxobtz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtkwxesjwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtlhzkofqp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvjqggzbb.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbtfhkmnj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtdcuypcvb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbnepojqt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtiiqnoltb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgluojbpk.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gteucpkszz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtoklttaje.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtgomgxseb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgrbkkxrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxkjlwlbv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtlkfuzjqa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtbaseiimy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtxvlsbmbk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtkhqoswvv.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtaxbafyrc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtvsxjjdoj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtrtfwuknk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtzecwkiqw.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gttqscazbh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtogodotzw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtyitydufq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtpqoxseld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtwxuygncy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzoywnwov.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtpfblmvfi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrxfkieoh.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtsxffmijo.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtiqumgdfb.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gthcoirbhf.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtijbvtcrp.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtrfdxtzdn.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgkzbytvl.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtfttkdkxo.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtlnebifth.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtvlutkitf.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtamxkpvng.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtmgtlfsiy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtknjedytk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcdxdglht.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gteedbrtpl.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtaatnumzt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtgrgfamjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtlsegkucp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgaiapebv.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtpmeafafw.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gtnfwpbixs.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtqzuewqpp.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtsicodryb.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtbjruhbvo.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtbdfsjfkr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtclkgswpi.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtjnbmpacp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtpqddwibt.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtjmwgmrui.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtgdmktnda.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtqszqylbd.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtmjeynywi.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtdvxbkiaa.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtrrvpmwib.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gthaqrxfkd.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtiudwjsjc.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtjwdtmfav.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtlromewit.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtittmnzdu.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtdwywtjuq.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtvvgoojvd.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtjnmjnapv.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtkvwkfvps.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtqvkkxbza.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtlxazfnvy.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gthshnhwef.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gttchyfkrw.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtckvwtyut.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmsohqbij.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtewwetpex.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtqqxiqrpf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtnfgmskne.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtsepnjogc.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtdapzwzrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtufxrqhed.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtxbxtbgxb.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gtwvletvfh.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtnliaqulc.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtujpdzbws.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtyjwoectw.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtphrwnxjh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtiyzbtqdf.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmvyiquq.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtvcxvhlyk.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtjwpbrfwu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtwzlbmsla.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtmwzrjlfw.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtxamjqsyk.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtexhxtahq.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtldpkgilq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlxvrngr.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguhutamy.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtqwupcwug.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtcrrgmjwx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtqxezqjyi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gthyywlivd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtmbnlfbuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gthdybgmac.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gtedzejkxr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtwcsrngux.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtnldmvfkk.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gthiitpwpi.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtjehwcfpv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtcsioksbe.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtfrjmszkf.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtkkdbinhz.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtgiokiwbj.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtlbfazljk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtpzpfzseq.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtudsdystq.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtpfkdlggh.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtnlnrtdoi.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gttbbntlyo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtntystbbj.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtblewqqla.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzpdgicox.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtpvtfexcd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtowuioygj.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtupupwhkf.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtvgmdksdk.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtikkzmqcw.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gttkdalqcy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtuwpgqdud.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpggjgwsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnxbkpm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtauprvxwp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtirpqovmb.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtsnrbqxfr.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtzhrdxljw.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtwihhoxej.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtnywmkdpt.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtapwmvanl.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtmoilcvwk.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtevsejq.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gthbnntosu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gthwwtxwfi.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtlrsbwtzh.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtkeemqngm.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtnyiixvwi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtrrzpgbmd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgzdxlqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtpgylalvt.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtynzhmxnq.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gthxwdeggf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtsdcsafpq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtjkgoknlx.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtyzvbiwvn.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtyffgsxwy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gthduaiwsq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gthbxgeugx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzoxbfot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtupbbhjfx.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gteehscdqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtsokoskxa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyhiywiw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtoyxdqyfm.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtwiyerouy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtgjzpdqmp.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtskdwulyg.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtriwmyxpw.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzqswielq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtnkektxoi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtvexmahht.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtyurukltt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtesangxjg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqctddmdy.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtddfiikrq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtebhmfl.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtxxlaxdum.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtnuzggueu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtpoygjvfd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtxjolfwmw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtrgecrorv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtczoyabey.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtxzhxhctu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtqkwjbzvp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtsfalwwsq.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtcpgvjjuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtkrfoehfd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqqowujxd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtjxuenljk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gthsnyshrw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtyfvwrxst.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtlihoeuul.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpygtjji.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdqdgwhdk.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gttdqthwpj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtjwuogmvd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtxvjtetdh.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtltglozrq.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtcxengjdm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtetbbrgbg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtturtjrxp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtjdnqrfpj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gttkmlynqo.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtgfomcwti.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtqqmzbaer.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtffzmfhsz.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtizmnrxnc.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtxhnrpxlt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtbjirwjgy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtxerkfcwk.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtpjlqvgie.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtewucrxmq.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gttsqeitxe.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtubakwdws.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gthietmzcj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtfbqgrmjb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtqkhtthrp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbfhpekt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gttbfppaxv.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbzrdbpu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtyromnxfy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtcbttkqwx.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtvntjfybb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtstdfaahh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtaaokidul.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtchyobocb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtswmngrfz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtqtgaywcd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtlihooqgr.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gthhokezmt.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtllgletgc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtlsaffphf.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtpmfkqthp.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtsantxbog.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtlwhrmwzz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtnpayvuaw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gthtxsmsea.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtyigchbzi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtlvkdgmdz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtzjudguco.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtmmzwxrzk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtwtbcqpmd.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtzwxvzykk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtxdcvsxxk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtmmmvxkrr.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtqtnkadso.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtjowreomw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtjaxohogb.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtempxdwvd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtzjbgvsjs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtsdczgpnf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtnncbxasq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtkypgpesj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtzjyzkqtb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtfxggvfot.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtvpfrlaki.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtbkouwlsv.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtsczwgoze.html


<!-- 参考信息 -->