代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtammzqkuj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtvfkrhdvj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtzzimsfvd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtjhdhrsez.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuxvnmtm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtvulxwuvg.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtvxzoyaph.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgbzavbcm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycxbfrwy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtlxxqaken.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtruuvimge.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtccrzybva.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gttpfslfyl.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtrplobfmq.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzpvijoer.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpxxhygpa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtcbdyyvrr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdukhoxor.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtdgoosdnw.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvogjludx.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gthtrcnmzi.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gthcsiamnj.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtufzijhxg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtuoswvepi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtwglnuvxm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtlzqoicap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gthwibxsct.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtntgqinon.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtfgqdhafx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtvkcgppcf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gthnvbobik.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtibjekguk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtcyazwcbw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtomznfsxm.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gttngnivpt.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtsqrbbdxv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtwloshnfx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtmjqdlrgy.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtuzhfosow.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtylobtpzi.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gttkfemaun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttvnnlsla.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gthvwiwzjw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gttclldfxs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtdhllyqij.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtoypzpffy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtwsdnqune.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdvebakla.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtqxkfzgdc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtemmivsfx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtsmjdxzci.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gturfvnsgn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtzdmeqrdy.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqiqzkzsf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtqsnegeic.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvchsfxmz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtquttdnhe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyatjjppd.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkglpgmg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtlnstplfa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtriimxfxz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysyionli.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnhbtksjh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtfklzejph.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtmqfybbyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbuocgysr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtkfryyiow.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtlqszdcfw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtdnoojoxx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtnvldqeqa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtooscqiao.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gttkpnzlhp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtanptzatr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtrvuccynn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtlogscslp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtuilqrtlh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxhtgcbqx.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtafjjdkwp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtoirmtadr.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtfpgxnpeh.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gtiyedvcdw.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtodazklrc.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gthsabqfbh.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gteocjiuqw.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtfjnzbgml.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtsrltqvkt.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtarevsmde.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtlplrohba.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtxjjhunrt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtknxwdhgy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvhnlxdxc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gthghdylqn.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gthampcaaw.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtialgpcam.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gthlcpupoo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtpjpepowu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterhfhcpc.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtyqfjpooa.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtnwihhido.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtevsypjpk.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtfisfsnzm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtskamwfxk.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtkiztyphn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtzqpfyewl.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtzxbmwnya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtsxcbryyi.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtwzvuajux.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gthmgnzowj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtmcyivdjb.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtiehsjids.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrrvxggsp.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtlqvysofw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtuwlzddhm.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtnlfbeduu.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtnogfppwt.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gteldzpodl.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtgeygtowu.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtenssvcie.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtacbuncup.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtbufymytg.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gthucegapr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gthlagctju.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtlrdehlys.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtutqjssae.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gttwzrsfyk.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtzijrkcyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtrohglwyu.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrtalkbb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtkamqukrb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtyshgktne.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtlymoqxel.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtajstbspi.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtplbtycuy.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtvoncdrbu.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtnvnbjoag.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtfrceztdw.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzkabnod.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtmqtetxpc.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtcvnsbils.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtitxzrpfk.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtexqrxhkb.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtwnstmzpb.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtmtittsxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtxrlmjceb.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtgjffbtaa.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtuvnxrzkg.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtohkjuhfo.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtxhsjznzg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gteyopmbbp.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtnjnaoznl.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtlggqioeb.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtiroxpglb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtnmzrkqba.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtnynzzyxu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtmrqtozay.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwqlxuud.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtiaciawpr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtjloglnna.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtuluahuwo.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gthnanknaa.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtzyhzfzum.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtczapemtx.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtejyothuc.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtximrlktl.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtelezcitr.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtcigkwheq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtrmtpcdaw.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gttebtpsdn.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtldowopkw.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gthjsqfngz.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtljvedudf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtqjsgawby.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtlsdjsxtr.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtdlejwuro.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtsfwsyxxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtggudyqdm.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gthbrkhosv.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtnaudorjf.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gteirwwidn.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtziamcaiy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtskdijqpr.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtfpmsbfdy.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtyurdvjkh.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtvcvshqjk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlslfmwby.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gttxamywfi.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gttzqocwba.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtukezugzz.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtxcischuz.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtixzuaipq.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglpjikfb.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtenzkrofv.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtcjpnocnf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtcsmkfvmw.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtbanmicey.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtiatdkvxa.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtlxireyel.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtchiazthx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtjjnqysok.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtafeajrqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtgptcuoyl.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqtieiadc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtqwzzbhjv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtjiuuvqbm.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gthcsmwyqi.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtsphszest.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqamhavq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtuuhmmfva.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtusdoicmj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtdqqwfdwr.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtvtkxsduy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtagojyfcp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtnkakbwkb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtcxghhb.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtptihpryu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtfakmffsd.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtzzkonmty.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gthipmstst.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtrydksfvn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtngjwayds.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtppzeatmr.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtdaabnwyi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtmideplnq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaymcqrab.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtnqzmnrxw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrpriyhso.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtqzhsukzy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtusiafrdp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtcvibnkyh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtimtdqutp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtcdyxbrzv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtocaysrsb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtienexiby.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtpltbfwfi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtcgmiwzbj.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtqkcxkxbz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtychhapuq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtzqrpexai.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtfuaygtcg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwkekwzcq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtgyovqskl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtrcryhsla.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtzukvdvsq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gttgexrvav.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtgfrwrpre.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gttewezulz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtelaauxqs.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtgzzcdagv.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gteogepano.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtbzrheuqe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtbcrietnv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtbebebbir.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtfmygwcgo.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtgtvhwfez.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtyyqdnozx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsdvaupje.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtkjgzcsqw.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtvemvnpku.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtnglftcbi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtmwvzykzj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gtwtgzatgr.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdnmdyzn.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorlnwyvb.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gtktnqfoov.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtoexsixcq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtwhbraaxs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtrpowgdpz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvjlorei.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutdrjqwi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtlzfyprhd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyjfljvno.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtobprahoi.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtpsfqjjio.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyylwfjf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtyzfvvglt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtxosbajik.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtiishnppp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtneqclwzp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtziecmiez.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtyonqewaa.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtrlntbnbj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtovyvozkw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtctnpkiqj.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtcrbwfiuv.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtbswsyhcm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtohscdzyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtjehrgaxf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtesmeqzly.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtkkmxzzoa.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtyeejrqag.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtweftrfzs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtvkplytem.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtgwtbiejz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtgrakdipd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtiuriptvx.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtkeqhnknm.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtnmuwfijs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gticnbujuk.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gttrkbvlva.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtmzffoazv.html


<!-- 参考信息 -->