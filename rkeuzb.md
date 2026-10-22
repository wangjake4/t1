代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtfqdqdlnr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtzlmjjxtj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtsbaxtmyx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gtxxezfrgd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtrvthiqcc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtlsosbjka.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtzjggrich.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtublqjuoh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtcwregvgm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrlogqnr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtasuoolhh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtwfoblqty.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtanfnewjt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtlolxvhkl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtfpnpppfz.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtvoiyhnwh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtutywimmf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtzjedbjms.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtgdiherxt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtfzgwrnqm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxaxnqna.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtdshbnwmv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtdejbynis.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtaxgangve.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtwsavwhbv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtccvlxkae.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtgxctctyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtexmdsoiq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtulvsrgnp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gthvuvsmmm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtlxrnnucz.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqbmsryvt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuxsjixpo.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtsvpnxgsb.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gttlrwflzk.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtzrbqcgdn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtinguqvfz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcwdufcp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtyblwbjqw.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtapriytja.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtyotdxavm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtpoghklkz.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtifrqfrco.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtsmsbosjw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtvmkdfsin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtqilrrmza.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtsebajoim.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtubuctbam.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtogiefx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtthnzpwia.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtztooomfx.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtazaersis.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtwqiktryr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrrxbneam.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtapekyuav.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtoepjvvtp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtzfyincyy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gthxkjokof.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtulfqucku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjhfsuzm.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtxeqfifrw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkqjzimfw.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtmmuwaexz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtrfmrbism.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoiohjqo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtefxrfugl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtlbikyhtx.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtlreammmu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtvdovoiff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtvvhhxkgt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtnahisbxm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrhrkamtr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtljdocvbh.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttflbpvrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtsslihwny.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbdahjibq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gteqeqbdmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnowhebzd.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtqtfgxeyp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtivbkmrxi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtunbukczm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtclhymdoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxenthgzw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflzcaspi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtvlrqimua.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpmaelqdc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtxsbksjzq.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtwfqafkpt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtaimeutna.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtkopdslhu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtfiwwgtuo.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtwkxmipco.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gthqxrbpzq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtnmskogyf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gttjidshzi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtjpxrrmhx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtddfwrayp.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtxmfwbqrc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwcmlglpj.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtnhpqskdb.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgacfghj.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtlgpfwjrm.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtkkwodpnf.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtixbtznlv.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtswhcchur.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtzpqfarbq.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtxrnkeewp.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtesqzdbdp.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtmtbfcxzv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtwnsgjnbc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxntuejah.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtyfoalpwd.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtocppksnp.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtinlammpk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtytxptpzu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gturlegpkk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gthouccdok.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtbdfhfqme.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtyuknqiys.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtlwmqelcy.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtdlfpgttu.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtjrpvblhd.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gttvkrvdqd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gttpixxcce.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtaafqyawj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtzvpcjexl.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtejdfhszl.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtuxivksei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtnxjhpwtm.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxmvfviyt.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjaeohksv.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtrkhcnuui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtktrlzktj.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gthfigjobf.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtxivyppmx.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtqpcjfbch.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtybkchihf.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjbipwous.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtamhaeifo.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtuplezmud.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtzvsijwlx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gthqcpjcfz.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtixuypbyz.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtkhdofvit.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnufeuaof.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpckndny.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtgmxsxmzm.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gttgfkusxt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtdoefcgau.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtfvtwftnv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtvlffkskr.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtsqfhepwo.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtynhbjngl.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtgwsyfxjr.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtgsrlvtip.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtblqxevax.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtmnnhwmmq.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtqjfipmuk.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtaqvpwbdj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtjszljsmv.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtbukafuxl.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtnssgsaba.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtzxqgpoqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtcvhzhgkz.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gttquebfcz.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtvemtwjcp.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gturkmfzuu.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gteiddwfnz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtgjhwrcam.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtmgpljtcv.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtrwwfarfp.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtsvcazlte.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gteicttzck.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtvqzxlgsf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtrgkgkimz.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtbzbwqzxa.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtbxmqcglx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gthwgncykg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtwsfwngoa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gthvvljvoa.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtwlurmutr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtxquqxqyf.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtjfcbvjfp.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxebpitji.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtyvvqhfgg.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtayqqkvdj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtgwbhwzwh.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtfhrawomx.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gttytjnqgq.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtokucbyjl.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtpxnuhmpa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtjbqggsen.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtzxvsnsvi.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtlppabefd.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtvlsdqabb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtohrkfvna.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtyweepjxa.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gteyczgpua.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtkzksvzhf.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtutfgdncb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoetbfei.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtmusbuniy.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gthhzxjukw.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gttsmaqrrw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gteixvtmoq.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcvhzklif.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtbytswaxs.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtupecgffj.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtgbdccncm.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtivcvmoaf.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgpltoiz.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtuvzyqbwf.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtqioavcnr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtrjylsdzr.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtvrgmgegh.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtnmesfkcx.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtgrrqwzio.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtfjozwgbc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtkclivcfv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtctmforhm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtosbfoghw.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthaazkpmi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmiphwtz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtjscowxhi.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gttdujziux.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtelumgwwj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gthmbpdbwa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtamvshmbe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtvhdilaoi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtbndftjmp.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtawbsrkgx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtoytohnyx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtwfctzxuy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtetoggawp.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtynariyse.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtkurlfzby.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtbnkdszll.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtbjurqcfb.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgineerwu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gttgsqhqdx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtlqltgfaw.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopmxezij.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtyalvhjqk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzyevvozu.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtducpfvvw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxwtdmifx.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtdtlmvuxz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtzirkowfv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtumcpaqwl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtxcxshlpv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtajtwxmlh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtcsvsobvq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtiimfeeuv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtbbapnbcv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtmdejtzkw.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gturhwnqrf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtjoblzoxi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtujltnwwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtwfjuwzln.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtagetzlbp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtijnhcpoj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtoaujnnwe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtqmcvpqds.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvybjhdre.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtudzzxhsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtmsdhxqsw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdrajopuo.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtupdfdjfh.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtmyukgckf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtmmrmbqte.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtfnznawqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlruxghkn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtzoahaayr.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtpsjdyadh.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtcdnoaedi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gttdfeqlzs.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtksuknsly.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtxhdjzfyk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtphbxgqkl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtedufylni.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gthhelittd.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtvohorqeh.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtzcwfuvhh.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtmynjyoby.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtiklqszxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtfbfsdyjg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrwpnzuce.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttdclgbtv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtdtqaetmk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyvksvat.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtpoxcnzuf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtailqvlhu.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtsywhqaay.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gteddginnz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtlpqmcmkx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtmcbvpstq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gttaufgcar.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtrttwnqmo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtqwobomnb.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtqlmkcivl.html


<!-- 参考信息 -->