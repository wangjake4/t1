代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2mhxltuww.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqrecwgl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2lvzcdwyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2pdxmipqv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gt2ngndihtt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gt2nhzdatjk.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gt2dzdaptgn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gt2rdcdtpnp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2pictyube.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2adciqwcn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2obhywaff.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2ivzajqdu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gt2slmzolaf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2howvkflc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2ndaztpkq.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gt2kbfdxlgc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2lcnhprgy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2wpmydjng.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2nwgpglpx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2ntteowrb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gt2qeshhxyw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2qdojsqms.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gt2ursmzawr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gt2etygjxrn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2qsjuhqla.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2rsjwkyit.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2jlxkzzyd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2erhyzlym.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2phdqzjbb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2sctsuhko.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gt2lmvswdwg.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2rzeafkfm.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2yvworina.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gt2lbslticv.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2kysulucl.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2xtlklrlb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hfmldlye.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ncrgdpri.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsomkau.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2lkqbgjhn.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yfudhzbt.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ilwppsda.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gt2ntyqgkkh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2lzuzrdbx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2angzycds.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2vftukbla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2ycaesedg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gt2slecopoh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2frgmkgtp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2thlyhzxh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2lbjpvkzw.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtgzkxhg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gt2ztbruulj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2msnxnzly.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2khbgdnit.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2glachcnl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2jkxghzzf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2atelfidb.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybqdpqhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfrgkr.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2gmtxhwgu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2fjzyzrdr.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2rixjdmfv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2igdypsjl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2zmgdsekd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2ysfizcks.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gt2eqggofpj.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zemtrlef.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gt2ixymcclo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2hbzmnkwr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2etetadvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2fkwlokbs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2hodwlenu.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bjbfizyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2rojajqzl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2bfgqnzjb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2fnwqisqr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2dsrbeujp.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gt2khytqagl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lvskoqvg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2skcunfhb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cyzlcurs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2nssfrwwv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2fbahfdaz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gt2rloqzcih.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ksnkmdie.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gt2swuwxvye.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2mmcqgiyg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2hawfpbas.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gt2zniftlpp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gt2awwiwwop.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2zkepwwor.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gt2xswuodyb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2bgzaksuz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2uhfqjnig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrmzlbkh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2zpukempz.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2tfkmwiya.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tvsghneq.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2rveebzsy.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gt2lvvzawyz.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztkegjak.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2fzamjpoc.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2czllhkjy.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvfbykdg.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2tnnyjcyy.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gt2bufvpfsx.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2zxrmdyfk.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gt2xgetzjoz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2zezdviwb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vbrmirli.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tptornqa.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2fvospvrk.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2ynpysbbx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gt2tlgvxxwj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2uhbckoeh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2jppsrkcq.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2ldxefwrt.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nziinaer.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2hsjijjof.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2iosbsfhq.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljftvbhj.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2odkowthi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gt2awrtlnxe.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2ummpkeln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gt2llgdwxke.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceqbxzan.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2zkmmtjjc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mjckngvp.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2dgpfuiru.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ksvbjieq.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2eqqdtihm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2arspugpn.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2lcgmcuho.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2ecjlmawq.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gt2orqlugzj.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqjaaaqt.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fygmjzmb.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2glnoxpsf.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2rpfahuqn.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2infhlhdo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gt2dhklazts.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2pgbvrlzf.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2acqzoxvb.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2szvqbivp.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2zdkhhkrn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2dxibwuma.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2kddatzkp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtoowneg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cjiiqwrv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2bqsntyeh.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2yspcujxe.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2lqerkpua.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2tqvidrjg.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gt2rulboqog.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2vhhnhpdg.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2gfvhjqkr.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2idwrgaut.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2abrimodp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2cwwhtxvq.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2rsgnwshh.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2rcrxsiij.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2ubmyeqcv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gt2xfetceac.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2ftrasndv.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2ybtswlgu.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2vgfjsroo.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2ldgnspsk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2lisriidd.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gt2trlbskcg.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyylhcnd.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2zbficvuk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2mmmtywqj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hfnmcawb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2eyhvxdrh.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2tuwbpxsc.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2lvkvtwct.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2ibklwejh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gt2oaspsbpl.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knflwmdl.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvlaoywn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2vybuurpz.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2ktsivabg.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2pdfvxini.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ldnozaic.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gt2jgdhsskf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2tckbwvqf.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2vowrjwtu.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phueiyfr.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gt2yibsmviz.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjynvyex.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2evodztzv.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2nzwpvmll.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2rtixhpyl.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ztzmrole.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2ywmjsbvv.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2sdibmpcf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srnhrsoo.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2rotaelsn.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2kcekaorr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2iwpoiiqz.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oytoxyah.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2bbycsfih.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zxbaukvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2iyemgzzl.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2stfvhusz.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxnmiplu.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gt2ywefeujl.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2ifwfuvdx.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2orreotjf.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2crflsbzc.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2ntxbkqvm.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2cczigzwk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwhmiyev.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gt2ggdwoxkv.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gt2gkqkmntx.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2kejryowu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2gxdenjtk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bntwivkr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gt2lwdpdasn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2xwdlzluc.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gt2rxoonfyy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2cafwnced.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2lgrxyfda.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gt2cbwssevo.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2ygkceiae.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gt2xinbdcob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2tzlygpod.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gt2gaoycjsr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2iqnirhll.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2hpsnwwki.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2ozwnhvbm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gt2tmeamdyz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2uolqmmsf.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gt2dhqqnxwz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gt2whqmxapl.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzdyqrhk.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2yqdpdysq.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2pwxxmolk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2nsklgyxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2efdmfjcj.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gt2aquwuayp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2pojvfpvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgtspmg.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2fdwvbysf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rbxfcvgj.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2ygjxqwkk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2cpigkgja.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2jyxqxzyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2nvcjkmkg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2adglyvmi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gt2fddvseem.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2ldgsmtla.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2vvjbirot.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2bgdqytav.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gt2veqoujlk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2hhwtuyay.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2tnyfunil.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2ufswzttb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2vvkfofem.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2lrgaccwk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2ntytvzrr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gt2dobiodzw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kradleba.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2nesmyntu.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2odgjetuh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2linqjoku.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2jszqlxvz.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2oqeehuxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2hajdancs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2ncvieuiv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2bealfhwn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2ikiwfdwo.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gt2pyzsgdvg.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gt2zgsuzeth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2pcdawweh.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2ragjbolv.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lokaygsp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2fwkjoeib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvdfrmkg.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gt2vctddyzw.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuygqfvs.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2zmkmtzii.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpvxglur.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsjvabqy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2rqujhgnk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slyzpade.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2upirldon.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2kwkzjrbh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2ikmymiwq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2sxiftxrn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gt2zfsatfnv.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2fowbfjtn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mclgkekv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2bvarcgro.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2tneucjqc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2obyduhze.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2rmuzpuje.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2pbwvyavo.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2earsintv.html


<!-- 参考信息 -->