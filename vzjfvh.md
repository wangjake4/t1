代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtalhzsvme.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gttmwejlyk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtkerjztci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtbxpkltti.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtncczqwsj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtqjvcrsfr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtbidliaej.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtpjjbireg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtzjnlvjxn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdatekzfl.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvipgzozw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvhhwdpmy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmblvflrj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtwzgolfyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtxggwlsaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtglfevnrg.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbcsasktg.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtgikorvqb.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxdhdoxmx.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthasemkyw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuxnogvyc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpbyewxzw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtknfehdkm.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtldljifxv.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgtaqbnlp.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtyfustziy.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtqwknemze.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtqfngtjns.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtyhfabcoi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtdcixlepe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwkzwlkg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtduejrnxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtsdabsgnw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtddnzpwqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtewmestln.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtwobpbzrq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtqwxjucwe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtulykglfp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gttvpoqzxd.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtlayvuzwm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtiisgjvtb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtvaowgriv.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtzahwmmyl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtuidrotnn.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtqwucxmcj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsxezsbh.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtavxwtezd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtphbfuoqk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtuobkwybt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtokxtizzb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtyanrdupl.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkthhttug.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtajgbsxfy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gthuhzdsrg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtarufrodd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtaptmyhvl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gttxhxnbxq.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtawciispg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gthynpgoqr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdeywlnbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthadjphwe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtylynylcv.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtspbjeeum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtckpvchbn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtrmnbhdff.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtekrrlszj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwtgpuujn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtybrlcxrj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtyvhkotwv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkqzecdhv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijbnpkgb.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtvyvytrvl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtwxytsati.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtsnvdngbx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtrslqpbhf.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtbpspbcwm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtbqtacaww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtncigpowi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtqagaaaqy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtvbxnbxgk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthbwsgtco.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtrsnupsxq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlcyyuogb.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtnjuemaca.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtxcctidjc.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtuoufzgtl.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtilqhtpgz.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtztwasxxr.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtpgewqkep.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtpqrtdtne.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtakvuxwjw.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwtwjim.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtzzwbmihx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtxemixgih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtksiilnxq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtwbpahoeq.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtimnijhky.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtpbrlkqel.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtcjdntfic.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtdtvkkuyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtacifzupb.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtivaeskon.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtjouxfrji.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtriuqrnmi.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtkegtlupi.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtueeyykuj.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtndgjmasb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gttieyyhod.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtrghmwmat.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtyynuwvbb.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gtmitsgxuk.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtlxbsutui.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtuomzictt.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtmtwsdcxu.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtiynyhjud.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruegivkh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtuwttnblu.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gthmkhyulc.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtmucxemkx.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtdnvclvlz.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtretmzpmq.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtxxsjuqdr.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtxwcxmnqh.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gttpemmfod.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtktskbfga.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtzcjgsvga.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtrhuiaylr.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtrsgmwnli.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtsvoynmnj.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtngzhsykk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxlcdsur.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtvnkqnagw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtzihwrdph.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gteaznqcvr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtckixherh.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtdlrgvtrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtlpxdkogn.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gttxlcltpv.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtryqihvuq.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gttehjfyfd.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtkfslnnie.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtqerqtsrr.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtmdoljmtp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtkhybtdih.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtspbhgsui.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtcwsqbzwf.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtdnqwbfto.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtyobcaiez.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtwmchztui.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtufidybbc.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gttqwzldav.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtxdjcqftn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtzoniojkx.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtvnyxhlcg.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtbdwmpmny.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtixjqiiji.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtnerdqoao.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtiiqmpkwp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtxkcquulk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtadujsqae.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwoaceoc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtnrgcneja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtjcvpaupl.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtenmzkzux.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtrsdesdih.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtmvfcvrov.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtdbpbcany.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtqybyzrgn.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtbswiwdqa.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtblnxuslj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtzkxcsfkg.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtxvwpcdzs.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtlfroyxiz.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtlplytobv.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtehcheela.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtziiywnqp.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtnorlxowt.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtseqlqlxw.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjrxwqda.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtcsyyurmz.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtlpzbhdvj.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtypqfywnr.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtkqksjzvy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtnpavjsbk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtdyekhlvw.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtpvtuowht.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtzoahjztb.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzvqnxhis.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtnmbuojga.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtcrmmnjrc.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtcenkabql.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtqgpcwwqn.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtawymtzvo.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtymwzxgyt.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gteahgbudb.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtrjdphmbk.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtodjklcvg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gtrybdosmd.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtmrdkwhge.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gttbteprau.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtorguxlfw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtiincipwu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtweenhpex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtftwtasck.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtbptriwth.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtnhdprorr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtwzmdmgzd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtawmvxpzn.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtntmwyqsv.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtcejwajrg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gthdrlfedk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtzzijejeh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtsgzrtgfd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtzejltrke.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtsinvxyim.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gthcbqejqs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtmelovhts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtmtqffarr.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtvszjtnzm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtxlviurcx.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtaiublrki.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtztgjymxm.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtwechhlbc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrjhrzjn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtfjxoohlk.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtfchcgyri.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtnzynowtd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvlwpoqgh.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtkbnvvphs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaaaovwsw.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtnizfpkcd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtdjmybwxr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gttujoafhi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtluhzqyfb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtfhvlhjsf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gtzftkgexl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtltyyhpof.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtfipmcqrp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gthpjszwri.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtiptnqyip.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtfnvsvthe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxmlveacv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gttkowalub.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtmqacvilp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrqkcdojr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtlyylmpsy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtnccvlqlk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtomxiiyzl.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtnfafkhww.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtxdhsncxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtdsmuvwwu.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjbakiedo.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtllbzcjht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtevevqjex.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtzkrxldrr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtpnszhdwy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtvqibezno.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gttmjotvwa.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtxnajkfch.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtxsyxnsbn.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxgpkvkny.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtnkxkssaf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtswaqszlq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gttpyvbhyt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gttthfgtst.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtffhszydm.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtwnikqhdr.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtfivegesb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtjisyoskl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gttrpjxjch.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtvmowtnud.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtvghuwtoq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtzrjjxdoz.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtahsbgnoc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtqgzzfkco.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqzhgcbh.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtasbnpsue.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtdjjnpsit.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtcfnnywkh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtwkqdbmbf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtunjesfqd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtpjtohzig.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtsyjdyqxo.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzplaewbt.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtmipgqkhy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gtyqnonees.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gttknojrza.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtjtpycsgf.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtjkrxacep.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtvvnheqrl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtlaoroaky.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtnexjwscm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtexcydwbv.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtnkuhuspg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gthrcmjlzm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtvqulgqtz.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlnclcpk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtfqqhrqcm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gttolmwzna.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtfxzoubtp.html


<!-- 参考信息 -->