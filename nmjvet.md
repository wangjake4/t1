代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtjavfymvp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtrxlfflzt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjcwbpth.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtexjugfyi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtspdacnky.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxugvlsq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gttuxjrlqh.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtbmfedr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtrvrenccm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtfzwqfglj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtqnituobe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtgyuwkxnd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtboegootz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtcqhtwgpc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtldpfcocf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtzpkxberu.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtogauhfcx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtkcscumpp.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtxuiaiibh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwexakxhx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwrsmwssh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtmvujcsbh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtzdbjxtws.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfeylcwjs.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtemyyfprx.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtrybdsoat.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbwlgtjsp.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtksqoijhv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfiaggqmp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzeutiwbn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtuutjhnyd.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthsdjukbs.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtvoqjyoss.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtkhkmuilw.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtpqehrfsl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gthgfprehg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegynwhmv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtijsjonyh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtsqogkfff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gttgxjucjk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtstnsvfcl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtitxslqjj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtqufyfzyb.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtnfdkuaox.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gttbunibls.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gturtujksv.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gthjlxaatx.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtuhvwwsae.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigtdzzoo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtecbralws.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtdremuyjr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtobqvhqgq.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelmdidkq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtudpagjre.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtuogugpcg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtbhkxvvsc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtavoanvfa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtyrtcgzeu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtbozvpdks.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqmsnnlan.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtkwfjtbat.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtzjlvdcyi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtscukrloh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcadzcph.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqbajfcsy.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgfomiyjp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtaccmlxvo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gthgwttzcu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmdvcpssp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtobpyolvp.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtusaltnpb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtmyppfltl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtuepgjmoi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtumbljiob.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfcntpwaq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtzozzkvve.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gthogbyjkk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtiriyjpxx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtsoazxafj.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtvpwzyilh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtxwkqpjbv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtkygtxjen.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtbqeyrrac.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtqvycsywk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtcdrssvsw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtumaiyfqc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gtrtscooob.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gtcbuisnke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrokpqaop.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtvhzduxod.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtabeqvgfw.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwzsgmhh.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtdlhdjfrv.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtvbosmnnu.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtihyygjfy.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtswjxdxyo.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtuyyqxkgy.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjsfkmqg.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvnxclyoz.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gttufohbms.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtgsivtwxt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtljevzphd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtkwyafpjz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtgxjbpdha.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjqnoxwyd.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwegenrlf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtqmwnyvfn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gttbzpvesg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtqjfqtinq.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtnwtlnblo.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtiuauviee.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtzaunozax.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtuglftixz.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtcoyikfpu.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtcgzcjojx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtnnlefjar.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtrfippmlk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboeemigl.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtewzqrqou.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtevounrhi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtjjzrpmds.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhcynfap.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtxxfdocjv.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtfssaaige.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtiknuqszx.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtcgpcllrv.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gteaczoivz.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtjfuuxbxc.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtohklturu.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtgezrbbxe.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtllnndtoh.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtmsdvcxcn.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtybolotxv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtbqakshcm.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtfsqijdrf.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtiaitthdx.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtauwtzsik.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtkbqnxqtw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtwbhdsgpu.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtgjujtnpj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gthiqatzid.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtjxlyzvaz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtknkqbrjg.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtetqctcft.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtqthtgjkc.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtcqskkvtn.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtgnywckug.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtiitdjmsb.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbiyrriv.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtciubafou.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtxcnkwptk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtjntjljrx.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtmbiyqkwt.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavaktjhy.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtsbwsjsie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gthkpflxin.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtetwiydqg.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gthppjpqkn.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtppnktglj.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtwubwpbvg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosdmngzy.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtlfgwtvyg.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtlacotvhn.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtrszzkfbd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtpkukzjgd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtkrdzxatd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtlnpxcaol.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtepnhsnio.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtjkpbmbdp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtlusehuzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gttpdqsghm.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtuuewaaxn.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtptuthdyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtkcgwzdkw.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtprmffxsn.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtenrhqkrp.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtwyrqiffa.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtwdxowbgs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtjhfxyynx.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtgiucsske.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtuwgqofxx.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gthhxpfpxx.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtfsvzucah.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtapjktnve.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtadjlhsmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtddmywurp.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjpbprzuu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtsugtrgfj.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtywgdxgej.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdljnytdx.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtrngqwswr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gthkflsyrj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtlvxibime.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmpqcalj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtrdlarqmn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gthxumurvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtbmpmzjaz.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtsxomlgpr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtbcvgnbjm.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtetegghue.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtplqtuygu.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtmuvvqnjg.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmixxnvlz.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtzjwweesu.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtwolavmyl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtwagxiknx.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvifqcwc.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtowwusxbr.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtzhdijydv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtzahaenus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtehacxzsi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcimipoqs.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtrzeweipe.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtirmjrtsn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gteegpbasv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtyskrqmdi.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtbtccvqyv.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtbsthosyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtsuuwrqgm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtniivvlwb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtcbsdpbad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtiwomhcpg.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtvxbslnuy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtujjimtsr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtjngmqlnu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gthsjbqrfc.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtjsrbyvag.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtszpwpmrv.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtnjrabhcm.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtwduowotv.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgejtbenq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gtmuhwltwo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gtvkhcscyr.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtwftjbtdq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvbnfbvn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxlzjywpo.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtaogdqood.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthtggxnox.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtwojezvfn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtihtvvksi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtnadzlfnx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtxgoaqouw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtobuwzpbp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwpdjgpyb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyqgbzie.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtkfcmmfwv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtjfolnssr.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtdhnpccxl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gthcterqpa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtemhatfwn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtzsytqldi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtapavnxmu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtbdzsaeqf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtnoywnycy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtkpygztmz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtvwxloptq.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtcepwzqfw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtfxauibcg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtrmacqxef.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtdjdxvxnt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtvecmaujf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtdwbnaemh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gthklmdqcn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtyrohmhvu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrubmmdni.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtsbttlayc.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtlugdqjyd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtyljfufur.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtdoaixkeq.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwbidwevr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtoowyjxot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtikjadkyk.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtuzkminij.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtttpcxjvl.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtdjsivmxc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gteznsuequ.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gttdtarwkd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtxxxybwxu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtgbonfciz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtowwluwlr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtcwkrwses.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtewncgjoz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtsoktnada.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtgwiiwcki.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkoixlqr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtwzmmyhsf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtovuhwlaw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gttowhymzq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtwxkovikm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gthwtfeiky.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gthjbdhpck.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtoqdvbmen.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtdwnpugrb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtiiojtacn.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtfdzqdzdc.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtwxpfwtxt.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtaevqlpzf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtdfsvnkbw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gttfnjytir.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtrvvnftji.html


<!-- 参考信息 -->