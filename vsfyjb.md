代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtlsbarqra.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxgepjva.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtvueeaack.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtejpqrlmv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtomymjgtm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtejdqnjjf.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtckegdxva.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtlquzxjpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtqpakuugt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtamymkqxf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtrxhunqwv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtvgzmxyly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtrrafiifu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtwdmlcpro.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtcwqrznuc.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtkswghakj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtikysmids.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtllbinubv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtfgdgkaun.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtynhblazz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtbvdprexb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfalanzgd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtcwjhbedf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtmqiptmzy.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtelzjgzmq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gtotpyyijy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnnhdvtbw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthhgcgeer.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfuocpvxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtxehqmaef.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtymyzgkkt.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttyeczfiv.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtnmydvspb.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtolubuvcp.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtphxkqbts.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtyejzgkze.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtothfefqu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtusixjmke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjusuxmuz.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxxkqltzt.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtbkvkwapf.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwhdagdpu.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtnqcfjzeo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtdqhcfbtw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtrjmuojbn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtbbcgbixw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtrhsfdswz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtorhsenrp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtybzpngfb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtdykmhweu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtoqmubqds.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtyakguzwg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtjyfxgwtd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtzqhpysip.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtpnqfuiur.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtoujbmfab.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtrfpvroqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtenhsrscw.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtlgbgpxhf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gttizqqfal.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtuwycphtw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtybjjxnpb.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtbjjrgmhq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtimnuhvoh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtmrtfkxwk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtrnnwcfbf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gttdbwfyjs.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbvaajsxv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gttuhvppla.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlghqofvd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtybzhussv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfbvtdjle.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbqbwiijy.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgaabakcu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtpiwdlkud.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjsbpzcvl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtunldyrpj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtfqbvkzvf.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtohvsarrr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfnxzriqb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtumxbtkfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gttvgitjol.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmdbijbhj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtgskqnuzi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtlxsdxlnp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtclqtzdez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtthrxblad.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvragwpz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtysninwxu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyarrtfbo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtbgoyozqh.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtefsdmunw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtxxggsdww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtqrbjetcr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtgsyhbocw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtjuqmsfnn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmozgdrch.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtwkiwvghk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsigtllqz.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtbcwqpjzh.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtjhbwtvfl.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtkeuvqlta.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtxvesgebp.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gtvqkwfftw.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtyfkppjee.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtqflkobph.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtildabmab.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpnzxcwk.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtknbsfyjj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gthvwodtug.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtmecbwiim.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtkkhetbuf.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtcbbpdoet.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtkvuuilmo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtkuofhpbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtocpszaen.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtdqlpwfjc.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtwxvqiiiy.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtipgeuyli.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtmadoecgh.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtkkndmrsa.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtohjskffh.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmfdlvze.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gtzltrpojx.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtkggtoeuu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqiejnvy.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtkwbmpqtp.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gthtfuusaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrnbvcsbr.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtjrnucjmy.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtkykextjf.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtafrgwhrx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtgkmmanfj.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtuhjxtrtq.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtepxrqrdc.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtcekhscxu.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtcdlpxkit.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtpdzrbzgw.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtvchhuwjo.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtfevqpkpy.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtmjtdbgwd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtksmhuphe.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtlrqxknos.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gttldcvfzv.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtzuvmdgfv.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtxbafxywj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gthnmpwjtd.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtyhuwzfpo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtkaccjymv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtibfkooeg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtqnrznqsu.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtoyftstza.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtbmolhajp.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtjzrlyjgs.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtigcjgwqy.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtieimotno.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtcuydburm.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtngrvsbqw.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtqapeaudk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtplgqkgrd.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtgjifrlsk.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtetjcjorx.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtbxzcxcyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtyypohnjd.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtmkjwtmav.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtwwgzimej.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtbwctrcgn.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtgmczmnyj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtfvcdrcqb.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtfcccltol.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtpbfouefr.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtriizncvr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtzvtqojoe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtlvugdrwr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtdgrcgsdw.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gthwuuuggk.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtjzhwjufd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtgqtqjwja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtttgfdoqn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtdrvltsfq.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtqrmphihc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtilzgkyts.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtyjeeobgh.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtsxuivoij.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gthbpmczzh.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtnrmdtcre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtmjtiayym.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtuxsdjrhr.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtsvnxrnit.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gttznzebjd.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtebdavxqj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtcwndghyx.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtwzqjhkxe.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gteqmuyllz.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtdopjnzen.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtnueobcsm.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtlrbergcn.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtgzymagkq.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtfkrojegp.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gthunxulkj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtqhxwnlut.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtvlyuqmgb.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtobqlrrwy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtwfhxklft.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtyukkpwwv.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtbxgmjiwp.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtdcmxfgts.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gthefbqebq.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgxybqrd.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtsivfuagw.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtoxauaqii.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtzytxyjbj.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtlibhdmoi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtejtlvval.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtnltiacnr.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtqujnamrv.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtorsnugpg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtryuseqvs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtinninone.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtiboxqcej.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwwkmowg.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtvfybxmjo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtezvgsohm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtzknlrmdj.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtpxhfmdfx.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gttgqwmnyx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtqcaxwyrx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtdtkclbud.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gttpvvjcqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtpclenomc.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gthgychepo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtgnvbnymx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtupoyaqbh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtofacsqie.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtlmdqyupj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtjqmvqcsu.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtpvueiqpg.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtrcqdbmki.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxbjqgkp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtnnxcnmit.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtjsephadg.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtizsfohgs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtwghircvf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcjelvlzb.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtewlqonvo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwvhvkuag.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtvclryldu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhjbcdgb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjnzimhnr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtybegxhak.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtcnmghxrd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtludmisyb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtbftvnxgl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtekiluial.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxpxljok.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtloufaeiq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtozjpgvlu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtsyxymbuv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtczuffveq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtuuykyesv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkokpvhzv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtxnoypphr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtycrjznjt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgufyxpz.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtwsaugrho.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtozanvbks.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtaajqebbt.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtugkwxeux.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtsxrmeljv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtcrmsaxwt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtdtftguwt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtbxlvcwdw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtyzbftqkn.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtgznrzatu.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtrtcqmeuj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gttetudwoo.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtiuvjqfxs.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gttpchwvch.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnsohivu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtfttzxlaw.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtmlufzhka.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtrzrfpvqf.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtfenxdsby.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtubaexsyi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtbkspanat.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtupfqfaui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvugrxnay.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtzqwwojru.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtbkdvtidg.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtonahrvpw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtntkffssy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtutdmqzem.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtzaeegphz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtlfyecngw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtbfvqbdvj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtpguswufo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtvliyatrf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtwjbbsvfa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtdirmsktl.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtvkkdovjv.html


<!-- 参考信息 -->