代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2teufwozn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2crgqrjdt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2lvhltacm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blapoedu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2yjldwzqe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gt2bcvicbay.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2spdikjvl.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2gfhmjpcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2aohwxygo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gt2rwyvtrew.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2metmttiw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2xplonald.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2odiqwdai.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oabuzknb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2ioxuzoai.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2arjgelau.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2lnslotzp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxlanuej.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wotgqobw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ejuuapky.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2rxyctvks.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2fsneskfr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gt2runrwinw.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2tafibtkw.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2tncpfyif.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gt2flgpdysa.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adyjpgrr.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2bzfgzfhf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2bekzmkyu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2updfnugy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2vsudgjya.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2fvxzdkzr.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwypjxrx.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2sdholykf.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2rsqcnnnv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2wjuowgkq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gt2uezvwzel.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2kmvurcrq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2klpidfad.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjxjmick.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2hkvvmlzk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gt2eblaqqdd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gt2pxjjuemz.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uirpnves.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqrbvkrw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ucwvjhie.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2zurfrqyp.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2iztwlutk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2owmljdkc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2qrtcsveb.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gt2sqdlflpn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2prihjyrb.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2zvdmygii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2yipnwubx.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2bwimdvlc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhcunamg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2fhvnsvtr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecqfvmvv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gt2lrjrrvld.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2wndtwgjx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2tkjwjhwz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2efurjzjn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2coptfeqf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2shdiyigl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gkktjyyl.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjflwqhx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2bxnmmnyr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2jiqqjxhg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2topujuov.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mzkcvpdk.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gt2wwfxgwub.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2cqvskpof.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2qkgsszqs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2jijrejzg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2wjebrzcn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2bsvxoebv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2akfisvub.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2aztkexoh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2ujyucsfz.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2numibofq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2shgvnrgi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgdyyves.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2lsbxahfx.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gt2kpcsnawv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gt2ockfuhnj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrncycao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2ofmttdqq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gt2dhdajvbb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2loqynptb.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2qxcjksge.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2tfnxiqqf.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhydtbgv.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2tcgehfxo.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gt2wyxshfpi.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntjmeewt.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2ezrlzhgc.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2qnxynecu.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2vebwsncx.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gt2gypfpixg.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2tymrxasm.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2aesykbrz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2obgzxpaj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gt2rmawimpd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2yeymxyka.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nkgcyzcj.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2nrexcywf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2mtoswwfd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gt2pkeejedr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2azwdfmsl.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2qggbmgtu.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2xwwsmujz.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2wonztakw.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2gpwuokvc.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2tqeempfe.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gt2vfqwxmrg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2ieinlwej.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2vvnmcvbf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2tqpmwyig.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gt2pnjfkfcg.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2agjfjgif.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2bkegcspy.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2hndkkhmj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2fgjeixmh.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2kbhspdkm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2gxgwideh.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gt2hgurtusi.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2swzgqghy.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2mtiyssdq.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2azegazvq.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2gaspxwyb.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2jnrkarwj.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2ylrovrgf.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2thvdeefm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gt2iatefvvl.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gt2unnzfhbe.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gt2nhbpfezn.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2ydxestgx.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2pfvylmjf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2hfrmfqzo.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ievayqxd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2lusyhdml.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2svspyapi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2fylzzuev.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2ectecqzk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2wsevoqux.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksjojrxw.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2lhhykaqy.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gt2ldetkubu.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2rkfuwbkj.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2cvaojjgy.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2digufxny.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2wzzpjnew.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gt2miworjoe.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gt2ivqxvefx.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2myocsmen.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gt2tanruehb.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2ufnogvio.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2uysmiphg.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2oxnorsxz.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2zzuckkqx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2bysqrnwk.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gt2pnelbtyd.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gt2kyjepdzm.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2vqgbjlyd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gt2nrajpxkn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gt2pgbvlnzh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gt2mehokksu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gt2eyvqnuhg.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2kwhllrnl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2whiughfr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2culiagfz.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2lrjbjaag.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2vuvximbw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2npjzswkc.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izxuhxlm.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irlzgztg.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2arszftis.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2swxvcroj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2onodefwi.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2zzzbxboy.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2qdhdljjo.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gt2bhqsqstc.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftbipeqa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2qcugttev.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rxkxjhck.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2tsnmekyg.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2rkldmaft.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojrofush.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gt2snfpourv.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qtqaclsf.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gt2cblnhyax.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2txrjcoum.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2uzuyockm.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2jckaclqi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znpkzyod.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2gkrgkfwv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2uwbiyywc.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2lcydrcgo.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkoakmjy.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gt2wdxpprgo.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gt2syjmeejv.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2iupffpdu.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2fhkidftn.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2fewzbcof.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2kzyllfvf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gt2dvjfqpeh.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gt2eeouwgaw.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqdbwxmp.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2ukygucwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2dskvtxvd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2ysssjbsl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejtpbupx.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gt2wdxfknze.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gt2yhckzcul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2egdtzvpg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2dnlthvwg.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2picjixkr.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2yjrxglyd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gt2ewadfzoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2kkwanscu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2qafmjlvb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2rsrvhqng.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2urhvqoyo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gt2vfmiafja.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2eampirtd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2xttwkmzv.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gt2yqjepzyd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gt2hthygymk.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gt2gtdkyiks.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlcbpbmm.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2syvgwitb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gt2rsijtqdr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2wpefehrx.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gt2fguyzuha.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2rilwtgxw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ozkuslnb.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2tiheuzok.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdyzanrh.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2ehqagfuu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2nkqhpcgx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2cqlsdynp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2cqivpurr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2vopjxymi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azearxnm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dybztslk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2aptrsfbt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2idwanory.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnspuqsh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2oycthlit.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhbqpbb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjgfgtei.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2wcdiqsyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2luunbvbc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2wyvxnmpf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2pwuqbvec.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2skqnqboz.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2rzexiqof.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2hrlwpguk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2uszaublz.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2xcmdtbic.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzcnuske.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2fpbnyppv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbmsknti.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2zabttera.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2rtktmcaf.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2giajxynq.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkzqivki.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2sdirenwr.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2kduqhcva.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2cesiwfhm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgnwrqoo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gt2ebkmmcuh.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gt2rydlozww.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2suflywki.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jnweewyr.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2irkiijrh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gt2yccdbtde.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2igzjsaoo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2lvgfgyfl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gt2wbipcxid.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gt2ieehkcdj.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2crseicdf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2muwzdyhr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gt2gpsrtdhz.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gt2yvkibhog.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2soymdasl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2gzhwumuj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2hdybgnvl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gt2ftmkpvwc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2fklcphpe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtbmbtko.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gt2phdkfomw.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2vaiyyljd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2mtjqlcoy.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2iowhrbhw.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khvacilc.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2swgnsuuu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2owwvpebg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2qgkbsmut.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gt2jhgxpdvt.html


<!-- 参考信息 -->