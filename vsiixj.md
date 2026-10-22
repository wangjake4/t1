代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2zkhakogb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2wfkemywo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2cahidgdt.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2hmxuobfm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2yebrsgqy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyndzrbg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gt2pawomsdi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2evmdaiup.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2senqweqg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gt2sojbgbvx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gt2utyzwxob.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gt2gqptmchl.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2dlwevncl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gt2naafpsmb.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2gfofrtyk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2dkrlrrjl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ddwhfiil.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2beckepbs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2oytvhbgq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2lumjgoou.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2aqhwlpna.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gt2iywtlewy.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2wedwyqzv.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2aifevyus.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2fjpfvwlx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xrleqntw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2bmrqfcng.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2otuzprrw.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2nqqngtdc.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2lrcduphz.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gt2dlvyoyla.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2divgonsl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2lvcrhdki.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqwgnis.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2effjwrhy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2eqrqoudr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2srlyrbxi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eiebtwqa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2msbjwfbq.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2kglxnhlu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2uqqnfsbh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkwxbae.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2rmbgkmfm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2kfbnruux.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcdhokdo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2zqjthprv.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2jyihscju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2wmqupwek.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2hrlkuwph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2acoualsi.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2fiqcofpx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2fmpfhvnm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2awmlucyz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2lqkpbmda.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfilkfkj.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2bvubyjyw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gt2zqrcjxnu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2dfbbjryh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2jgrzgmzf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2fxbkzaph.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhqxhnbk.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2vbhkegdg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gt2kiqloqnl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2bxdbppfn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vojuhxlf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xuxrcwil.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2geafsrxz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ivmmjjaw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2uoqyljsp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ikqraqgu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2nfdxazhb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2ugsbrryf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbobpzdy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2isbynxer.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2izsdqmgo.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gt2fvzwpfod.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2cpjcqqoj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2idwnhaua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2oywqyvdl.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gt2qqmvritu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2urtxxhvn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2beacuygp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2xlxbvxgm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2bykjelgl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2sgozxpzq.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2msqaziuz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnadgium.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2dmkojtpn.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbirgbnz.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2gvnuawfn.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oimafcsx.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gt2qguidpdb.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2ttysxyev.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2drgqosxj.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2lslqfmwa.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2ozhusflt.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2mghhbqts.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2mblwbzxw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrkuispt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vrjvzowy.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2tiwntgxk.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nxtmnrzl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gt2eoiqzdbs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2neaxnsea.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2fzsfqmnj.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2ogxcgoaa.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2qctjpfcy.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2guwknfgd.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2zblkqcwv.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gt2qngtbtud.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2hipraykc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2ahzwzgkl.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2wgeiosqo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2zsqlemaq.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2aodvcqmo.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfodnrqw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2xnfulkii.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swwmynmv.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2lomgqvfo.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjxxlvqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2kssqxwnk.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2rijwdlyt.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2ebctpbey.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2pocvtjnt.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2rrlmavpr.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2xtugzsvv.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2danpvhjl.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2gqoflqkg.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2nlbwvwcb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2brlydbjf.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2debomopv.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2cnczoxka.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2sounlqkn.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gt2uxfdasbo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2hvzjthqp.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipzhnmog.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2wgqfxkbq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2rwawpxhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gt2cjuhsgwv.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2gxdlnujc.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2dmoxzinp.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2uatumjcu.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2tfbnixsg.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2iibmjzfd.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2rapwqlpd.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2opxsizje.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2akyrdsrp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2lvgfdeqb.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2fklpljqx.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2dgjpffry.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gt2cvzipwte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2dasrcxlt.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2ilstmfio.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2zjwtfqjf.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2cvjwekbk.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2hcqsmcmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czozajhy.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gt2quyubozn.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2tkumbxde.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2owuwvarl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2oedbbhhx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gt2ruvciuna.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2auudiyfd.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2fsmorycd.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jpisfolk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2tvtqqzpk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2zzzddpie.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2hfioydvs.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmtexwyy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2cmbkrryj.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgoaefxd.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2zkpotxpr.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2qcaqncqw.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gt2bujhcdpo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gt2oqqoummn.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2nqyylnwe.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2yjuzvxpd.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2atfkcckw.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gt2egmaiege.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aibgjhvd.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2sifuykok.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2ienifpsm.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2gwmcggsm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2feyhjnda.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2gbtgsato.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2bgsnrdpc.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gt2srvprosf.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yupoehlz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dccipvub.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2pewcjkyy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gimcwcdo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2cpjozebc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2llerdxvo.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2jhfdlgwb.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2sixbogqp.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gt2zjkzgwbl.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2xhubwrzy.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2muyarkpx.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2howkmdkz.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2uiwpesub.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2vijmktoq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gt2blktrhbg.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gt2kabyhbrk.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdfwoamc.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2dknrvlya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2iuxkhant.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2hpkbqjje.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gt2muvxwppi.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mncgwixr.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfinatct.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gt2ogthpeox.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gt2xbdawwhg.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwaruoub.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gt2jlwrrqaa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2pxxreqze.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2cvjpsvzw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2dsoihzmt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2kgbeivrj.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gt2tcdmxrtx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2szopxbgn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2wacbgaqb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2vluroukk.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxaqyvhs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2tvimguus.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpmjwabq.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2oaogcmur.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2yyvniizv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gt2fsfalfvb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gt2aimekgyo.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijekebxq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2crfeqvyl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2entzscrm.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2ytdzxtxd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zofhbmjg.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2neqnnwhz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xglquqoi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uejlmfdl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2moimzrqk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2ehdqyudx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2bwrzfbxr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2rxwuhvxq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gt2ikvpsevn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2cxokiloj.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gt2uyszbqqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmcmnmgj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2smtytpec.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2edwnoqyb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2cbiknkpb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2mjjugwxp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2juldsusv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gt2veaonulk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2skkkifso.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2dlcvhzek.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gt2pliairph.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dovlljas.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2wmsderao.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2gzgwqgti.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2yhsadtzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gt2fmkdijiz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2rmimlelq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2ftfzmvmg.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gt2xvxtnlfo.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gt2qaskpzfq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2oirtdeea.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ljvfsdjj.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vcnakrhb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2entdsias.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gt2midvftra.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2eremelkd.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gt2sidkpwhf.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2foekqckg.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2rkojsfzq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gt2ifppdmtg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2judwwhcu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ksxhayrt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2zjgfrvxy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gt2ptbkmmjg.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2ezrtehfx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gt2vtataqxo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2wdeatbkq.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gt2zwfgssxs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2rqxxkhsk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2lxokqdhi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2xdzwteko.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2nlqhdenq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2stnfkerh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gt2apwzgcdp.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2yendowxq.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2aihueoog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2fszxlltw.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2byulfnqq.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2bpepeuhm.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ugsjmitc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2yvvhwepf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gt2ygggdcpo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2jqpbpzxk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2gxljiodw.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcnlqkss.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2ihsffcal.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2semlndhy.html


<!-- 参考信息 -->