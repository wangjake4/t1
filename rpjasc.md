代发 wailian999

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtbmxmqwkn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtcjfvggkp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooxehcci.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtdtzwkncq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtjqjytsjc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtlgbsepzc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtdoyeeuin.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtskdzemmm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtllfnolny.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtjajtdjtn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtealnukxf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtlnzjbeaj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwwkbfvbz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjwdgaldx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtospwsbof.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtvjqqbsno.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtzftetfmp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtqabpdulo.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gthnisfbau.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtordkmujr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtgmveaqpy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtljuctaeu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtpaktuuut.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtpstaopfj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtzujhnorj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtptparklu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtbnjdjvoz.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtftfqdhpo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtkxninjqq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gtrhzyguxo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtixezixuj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtglfvcpyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtwfjuapyf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtzjdxvpmf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtwxnykejp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtoebyoxbg.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtkeawedpv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtfiuzyrwf.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtvxrwggud.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpxuwvowz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzlkptzoe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtsfgxqggx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtikfmsaek.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgrhcgksd.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfjjzxcaf.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtiomfuzzt.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtybroezgx.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtkglxihdf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxbdnxekj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxzxentmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gteemtrtpl.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvjkyvncx.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmktgwcht.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrzhxyczy.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtxkvrcdwb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtybolwvim.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtvreogugj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcqwcjlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtrbkygptj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gteexspjal.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtashooydp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtlibzbtfd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtujqgizvw.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtvgpwklnk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtinhzvqli.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtxxdiiawm.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtdsgdvcar.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtrlakyjpl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtixlkalbc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtpbyuvbmj.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtqnsfvqlz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtwevpyhzf.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtulravzkc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtojpbillg.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtlegwqujf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtfvgsepim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gttgfteehd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gttruolskz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtnexzgeha.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtekjxcwlz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtwnuvuohb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtaratlvsg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmykiirfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnvfdmowv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzywhlwae.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtippyegtl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtniwiqpzb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvukvrmfy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtthmtawcp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkednbylj.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtubidzbny.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtqqpajxxl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtabqmxwic.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdbnfhnhz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtrkblmrro.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtiilljkep.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtappyotoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtlnqisxmw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtdpwpqatu.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gtvwwhzpma.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtxdprkntk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtlmzahtrr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtxlaurell.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtolvrmvfm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gtvmvuesen.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtcjwczypp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtajgscibv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtvslvdvkq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuqhmlrmo.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtqgdcydrc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpkneonw.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtukznjiev.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gthtvmxael.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtxxxublgs.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gttpflrvou.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwarzzsy.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtxygvcall.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtqoqtvipa.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gttljrdclz.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtteqasczc.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbwhvhxg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtrgpoblpt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtzdfftqqp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtlvztrufy.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdmnkuuqi.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtytpazibk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtbvbjmkto.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtlapdybyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtdrwnmfeu.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtiijqzxhl.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtronnvjwc.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtfnknavzk.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtmosrmtpn.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmnfdlvq.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtfcaehpqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasrcuort.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtkfrnbl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtksrnpscg.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtnctixtsp.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtmztnrvxq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtgpixfwjw.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtqgznzjdf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqzdjuadc.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gttphcjjnn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtunyqoscl.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgnbmndol.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtironjdko.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtguxmvlem.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtlwvxpsko.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtfetdgbby.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtiokkaiqc.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtbqhvqcnh.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtlejzcyzs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gthjnnkmgz.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtwgoaicit.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtfwqtbosx.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtnacsxpis.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtsawwfisi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbwtwfhny.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtqkpeogcr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtqpkvveev.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtwogjblvb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtnyvjedle.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtducaqqid.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtywqoixon.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtwdsbjxiw.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtwknvxzdw.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtarkevxnk.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtxpkzcsnh.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtjdeyftns.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtdmzcuebv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtxgydvixb.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtnveatvyi.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtnlpuqhex.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtvxeybaup.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtyelivgth.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtzfbszaqf.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtqliqpasl.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvavhhgpq.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtlqtvfhvv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtftulftad.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfezaudnt.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gthlvtxkqt.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtxraimatb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtjegourxf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtszrrketm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtppffbhlj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtxbsygngj.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtfwmwbaia.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlssuyjjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtncraysyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwntndaay.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtfyuevdfp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtvdhvtcpu.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtvdazayvp.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gthqsjqmup.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtafpipnvo.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifokvhhp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtshsdhnmn.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtpkjxfmfp.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gticpspotj.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtcrakkewy.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtaetmodae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtsqjviytk.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtyrvyxffj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtifxhgidb.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtndzmqwgw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtlrfeyyva.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtqgoberyt.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtupoyovpt.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtvygfctxe.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtxjalmany.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkwpxzflx.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtjzrrzzep.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjznyumeo.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtvvrwfggs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqxowkquk.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtjlbouqay.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtliodpxfw.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtkehnrpoy.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtgfzphunq.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtjxpqwfpj.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtqagckjvt.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtmfvpmnex.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtabmfzato.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtcouzmqop.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gthncyjvyo.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtbvxipjyn.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnwbpaxv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtcrnsqmrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtnvemiwxy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtvqobsorl.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtatuxguau.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtiimlvkhk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gttfiwyluv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gttuwgkcqx.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtgfqdcmjn.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtggwgxltv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtvqfwbedo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtzpowsiqf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtaywlbmpn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtoyxtvzvu.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtgacmdbhu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtgeikpdnw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtuxvplhnq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtvakxthzz.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtjjalzpbe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtrhzzimbl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtwxujnbpt.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtjqachxeu.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtesbeqdyt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtudywlcen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtcyeqcdww.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtpncinvcw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtvmdgbuec.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbqludzsp.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtefckihed.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwagtowog.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtxccvusmh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtijkttisn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtkgusbuln.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtgxhvhfww.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtwvlkomlz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtzachcwtg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtmxlvhboh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtoeiumoln.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtgaccfnxb.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gttngulnre.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtvitaqpax.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtmfenjkac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifwvlbiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtwqgdvoox.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtymrwrber.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtluwayipv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtrokmemtr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzhwvpefv.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtvinfbxrp.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbjycegg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtwyhfovbq.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtlytjgumr.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gteecqnyax.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtzqtyxhqs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlbxvbnj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtqwqnhteg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtunlxwexv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gthrisbkfx.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtlxnmhevv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtmggqctij.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmvoxlfb.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtgehubncz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gttqpelted.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtbsvgucbb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtuldfiguj.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtzxflcaft.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtwzuyusml.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtlngcenbf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtbdqxrkai.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtypudvcop.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtreebihsi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtkvhherok.html


<!-- 参考信息 -->