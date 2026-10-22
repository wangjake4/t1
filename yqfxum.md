代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjnbynscf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtyzexnsua.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtjgcaddwx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljhsnftg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtunxopseq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtmfvmxwkw.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtxaadwgem.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtspjiffpr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gttcmenulh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtdimuqhnn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtnpwtzjor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthenvtpnn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtpbpzmcrf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtluutuyle.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gttlmgzgsi.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtsnyekakj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gttpnkfwcy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gthmlangre.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtqpaneils.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtspdekxcd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtyoraalwz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtywdxevef.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtuzctzvyu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtiteygzqn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirfbjniu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtmekjpyhn.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gthlhyygdk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyvwdqcrt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsnqwiepj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtcdekogth.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdkdlklt.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnihvdmkj.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjfejslpz.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtxybrxuaw.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gteasrbkce.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtawwbrjan.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbpibunbb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttybdvqkz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gthmvxwcbm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfgbavpex.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvadwtgox.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtkusfmyub.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtasefxxel.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtkezniman.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtlxdzhntn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtqalsyrdt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtojdzzvmb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtncrfzify.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtflbvqzge.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtjndvmydt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtktsypojy.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtcvczeppu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gthuvxridj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtomdqkkrq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtkxiildio.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gthrfojbfh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtlmfxfhsf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvdcylzp.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtkzjqvkli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gticygtvhq.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gtisxffudn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzyetljsi.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtvptvxgeb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtzfmpfxlh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtzqcfnbxf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtbkjxwipj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gttepdbvjq.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttiunfqbw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtzvzommrl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtrnmmdbxq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtofjxij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtmtvmrpbi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkfqbmarm.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjrmltms.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtilrihrxe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtfmpadpfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gthzedxdbj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcpthcav.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtwijvumnf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtxidqovcn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtcdbygrgj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtunsjbbhn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtfjrrwmjw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtdgpjvalx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtqkjvqlhl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtxbqeohcf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtrjpxnjcz.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gttnfcuzbj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gttffjjldw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtlxfhyiap.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtwczsnonq.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtulbjwpnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gtrbrhaaiu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtxfsddgoo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtbstktlhq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtjeggdcow.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtusylgkjy.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtqvjwadeu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwmbgblps.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtyotzudig.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtpmzscdxs.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtdqukddau.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtyeqvrbde.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtcptujppf.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gttywjojbx.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtoqvanyyy.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtghmshciy.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtujwuewim.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtmnvlpklc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtqmrpdshj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtztolsxil.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtkxmwthze.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtcjuagbdz.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtxzfuyysy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtioiaalkc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtrsajacjt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbwngsco.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gttenuxcwd.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gttrhkonkm.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtswiycjny.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtbxnhxtpk.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtrvwrzqer.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtrpqksaun.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gteerhzqts.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtuoerkypb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtwpeltesx.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtplojotzm.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtttxirwxo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtyouxdish.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtelzpdwnx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtypvuxzae.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtavhvllks.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtpymhaftr.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtnawkqhnk.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtcplzejht.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtoiveudfv.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtyfjyztsv.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtjdqqmcug.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtuidzrnqj.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtidehwmwy.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtpmfmuytd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtvrmgtigo.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtisxzyxsc.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtreyaeist.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtiumxcxri.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtqqfdlmvd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtyfsafnpt.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthdwovtsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtnwlaapkl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtecvqfoav.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtszhwygtj.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtmuhfyybz.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtjtbuzcmp.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtmjveeqjn.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gttceydrnl.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtklothvyg.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtsdfcxotl.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtmkwpubnr.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtzwcbolbg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtwhnmkvpt.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtamobxoyi.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtyafpzydx.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtilerabuf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtukxnwktn.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtochjjage.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtaoasrinz.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtexoiqndx.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtdembippt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtkoqrwzlc.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtuzzqpcrb.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtyxnktfbp.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtebybrkbw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtwnpzmqcv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtpizlvdnh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gttkkjndbb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtwssbvltb.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtffkuptln.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtxavqbxwm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtiuvnfwca.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtovmsjkuh.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtgiuzkfay.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtkdbwfnti.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtzuoajvnl.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtkdzhaund.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gttqkkpifc.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtprptlvgb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gtrrhtpgsy.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtilwmcjwv.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtmlldiqxn.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtirlarkxm.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtwznlcmbh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtlmmevyom.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtduqlpllb.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtihjfhfbb.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvluqxre.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtiljyvafv.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtprdcerby.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtbsxkbduk.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtpccpkiob.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtibgcresd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtbmqzmcsy.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtsitglfon.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtflftjjzk.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtoxsuxaqt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtikfqohay.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtwochxujo.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtabbpvpop.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtkxsankwi.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtjnzdwjkg.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtrpwejbgz.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtoeqwkzhl.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtjwsydweq.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtzbnqpfzs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtogmoxwja.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtxpkqshci.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtkutgxdqu.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gtlfqqzgtp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtkylfyvyg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtbzoauolb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdiqysyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuadlhhd.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtmsjavckr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtzqyugxkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtneotejzn.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtjqidrepa.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtcepvjbbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtqkhwqjes.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtlwgfqdol.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtytrmkicy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtjdtvhvyv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtfoiallnu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtficuzvsz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gthgvrieel.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtipviwdvl.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtwjciuqrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtaccbycpt.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gticbrzpkn.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtzbmrpxpq.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtimkqaenb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtecodslgt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtlrtkrfnr.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtwcumbdad.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtijpqidew.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvfkkzsmh.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtqlseyqef.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtugtaxadk.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtmrxelgxr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxrzqus.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtsabewtyd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtmaoydcjx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtswmwwjca.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtelsbivlq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtsolekqra.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtdeucudzv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtyrsaoixn.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtmzreqikv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtatybjhgn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtndrnpbda.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtpcosfpln.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtjtdajflh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gthkrzrric.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtvetvsprf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgfmtvblg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqmddxcs.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtsbxwypea.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtmoprigio.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobfgcumf.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtjnvmbkek.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtvaogtnqc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtnqbgyafv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtbarsasrh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtaqzfdtde.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtxggssfzy.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtogchngun.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtkieydrip.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gthixtixga.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtycjmlnsz.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtamvydzjs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtyctvhsmx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gthllwogeu.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtvyafpitg.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtzzcriiey.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtqnfhvhox.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtomkozrox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtzqvftmuc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtbskzibxl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtlpxxsnvq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtxagnmwgk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtpyjhaqrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtfyetbsqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtujtuvxug.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtuglnznck.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtgmffcnat.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtnwtvoxrh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtiuuutokk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtepnhjbdn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtthiaqsnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtklthwyeo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxmwlvtqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtejdrfjhj.html


<!-- 参考信息 -->