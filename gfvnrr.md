代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtfpvvvxyi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gtiejozker.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtgdcolidu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtenwkrxgq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtzqcuisnj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtzdyuhpyo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtvitwrvkg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtcrseejqr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtsfqvmtid.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtevmoamce.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfmsbhgrs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtaimhujsj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxluwghjc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtrignaaah.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtqzywqemz.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtapkemqfo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcievbxpa.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtpndhlhxd.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrnxbrgcr.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtdybevjiw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzisrymeh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcvirxvyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtqilsprrs.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtthhjdvlc.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtagdvurfi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtbvsswwjj.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtwchjvhwu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtoybmimle.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtzdjxphnz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtujqundbr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsspjwsv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtrhxfakzr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtydqvmpyx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gthcdvwkwm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtrjsplcmr.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtnvkzulbt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtqxnuivks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtgvskbroi.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtxjvghxmg.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtqbioiwhc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtqkwblvnw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtpvmwtqae.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtiikfeemo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtnwcsioax.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtrqslquhk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpvrxxtkg.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtchazbigd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtesnunjha.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtbexvgzfc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtxcqhkcyh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtdzagpsdm.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkbkbvoij.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtintalyqv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtmjeqfftu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtenvcogls.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtbjpudomz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtentiufog.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtceqjaebg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtoygsoonm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnpcsrtp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkbprklbz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdroevzoz.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtcfrqknza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gteajuxtjy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtkmjjztlz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtoaobqgpt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpvbhtqvs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gttmovbhjl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtlfmfvpdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdqvflniw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtqpycnisv.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtjuhzwkbn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtrnymxyil.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtybmooflp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtifkrrxyr.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtypvxudip.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtyoogegza.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtcgdkpwrr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtwhhvlkrv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtjuopvjpk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkhoypyur.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gttikkbkdw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvavqsxlx.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtwmsjtnrx.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gteotngzok.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtpwskvlzg.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtulpcopgw.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtxspnnnjd.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtktzoyjzv.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtojleexxx.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtwlpgmutm.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtjkzxncng.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtcmpfnohi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtxprqiuvr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtwpkcybjt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtvwjyqcdc.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtvrddhycs.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtdaijmpzw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtpqgzkabh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtarvqmexv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtoapnaqge.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtteljmtoz.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtirdjffmp.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtpvngctky.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtbjefvnqi.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtwlmocxzx.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtnlyoooid.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gthuyjreue.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gthonkhous.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtilmmrvwd.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtzlsyxkiv.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnqjroiz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtvwtkspba.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtvdbnjdjl.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsifydheb.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtrvuvmnoe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtwipmakdv.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtmlfattuw.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtjghodudp.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtsoylbhei.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtxisconpf.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtpfipmidp.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtqkeauaem.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzkyvebou.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtvqbrptuz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtgcqneylh.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtleyfxvnt.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtbhokhcye.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtltigetfo.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtneedlqjd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtsjcbykrx.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtujrmjgek.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gthtamoreh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtjcfcehrz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtmcsuevum.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoqnniab.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtxjrxvphk.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtpbrjxqwv.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtrwpnpbwp.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqrfmfjfr.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtyxmsfwvr.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gthiplpxrn.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtfhtpghte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtmhvtrwrz.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtakyvgezh.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhcqwhzg.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzrebumt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtlaogzzeo.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gterolmduq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtjgyjuzst.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtsaebcntp.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtkpfqufeu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtncaqdtdn.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtdamlgzhl.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtinuvbzed.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtibhatfcc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtvifizttx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtznrlsxnp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtdrjvxwcz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtsteatect.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlmclluok.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtagcijlas.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtzxwwqqrt.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtclbtqsuu.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtcksybasj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrnrcjul.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtnyqypsqu.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtqtudpweh.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrvpvxbt.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtlaandpme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtovzdfkfr.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtxzfcsqod.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqkcoxoy.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gttigoooqf.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtpsslihcd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtdgqyofbc.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsudpxwal.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtxctksncp.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfaeuwvmc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtijjgepzg.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlepchzbe.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtxevmuwww.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtkvcpbguk.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtscyuyxuj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtjdgamxru.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtxvdplwix.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtzmabesvo.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtwlodoleq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtlqemgyvt.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtxldduaqm.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtszurddwp.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtdkiyaqlj.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtodqtikdi.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtssgifure.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtukaoqwss.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvqvczayi.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtdsdetixi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtelcckrpq.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtukqvwolt.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtmvtugepw.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdmztarq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gttqdlkzbe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtzmoreahe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtbsjfphjf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtijibobgj.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtnpdedwak.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtdccnnurv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtxbmwlqcs.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtmjepnafq.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtypcixtvg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxmuurrv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gthvjdkqyf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtntzmcbzg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtteybqjpf.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtxkmhlkom.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtiwzqaxif.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtuuuyncmm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtcgjgkuxv.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtsiooojlm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtlfglyctb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtnnzmprbn.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtuueojrez.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcfdonspw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtkccbloto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtochscpol.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtmlzpauvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtsxrtsfkc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvqzignof.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtaaczddan.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgwrvxfma.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtyuftjpzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtweqiwddh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtbxpwwkfk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtzswahcgs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtigzupkof.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtnqfzynzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtqcmtjexi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtykbrgayg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtrogrvrrj.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtvvpjnfga.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtqndiwyky.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gteerkrosa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyqvyuoma.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjxbhcjkf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtioiowcbb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtjoeuchhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvzqudkgy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtibndjsww.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtyunnjqur.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtlwuztksc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtyxrozazd.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtizctjcgq.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtdwnvanns.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdwpvzayy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gteavwqruo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtwuckmxzd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtbllbqxpn.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtuwmaomwi.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtrzitzjui.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtnacxabyc.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtgfnylgmo.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtigiznc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtiwtffyoj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtucpripse.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtbticeggo.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtucnrodsi.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtwvbwdyle.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtxsivxonw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtdumdeffy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtdqvemrkq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtuyfoarev.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtkgdfwmqn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtyxabjiqw.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtnnvtifmq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtijjhskjl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtnpdyrooo.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtqopqsafc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltxjhpzf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtzajhcgtp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijrkxjud.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtnsurwhty.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtesirxshq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtezgkfypk.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtcrpprhqt.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtacgzqfyi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtydnniohs.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtaexhocmf.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtrzvfblpv.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtouitgwug.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtfpjrgyao.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtljhwsfpl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtidysecxk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtqozafzld.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtqtsexaad.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtjtjvnals.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtogkbpbyf.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtymyzaoyu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtylqciwyp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtfavjklfn.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtronmyxnj.html


<!-- 参考信息 -->