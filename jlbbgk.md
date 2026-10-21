代发 wailian999

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtlvbsjuju.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gttmebnkvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtfbitumvb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtsulymhpq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gttxwtukmq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtfjvtqqou.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtrcllsdck.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcvfpkxxf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtgjdufbfw.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtewgggesn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtniunkrva.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtwkbveztk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtayyjmaiv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsomincbj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtivwcvsnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtqxpzrsyi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtzvfpmagj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtndjdwugd.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtgeczwcej.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtefdccttw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtxcoqhisf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtlntgjeyh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtkwzgpgcc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtobyuxzmk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamtvxlns.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtpycndgnx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtekqodvgi.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtyhvzvrru.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtgeelnqps.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtovqdptat.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtggmdfsjn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtuulafffs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtxyjbxnkp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtlmupiram.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gthjjuyjba.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtumnfcjgz.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtwtkjjytj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtrhefwkgd.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfgfhaalq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtcllcjdsu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdtazzkas.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtvrzfhqev.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpftroxg.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbwlfxzdd.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbpezafxf.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtywigpejr.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtexyzbqiw.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtoqwcuuad.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlgvgeica.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwysimwdw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtqisiwptj.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtudjfrfrv.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqowfouef.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtndwppvfv.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtwczcecbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtrcgjoazh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtaujayekn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtvdgchpsz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtrhtdqdat.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtksmhniig.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbttyssw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtkfuyytnp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtwcimripc.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gtakmoitwr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtfviyrilm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtbbwvsqvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtgmqcjfrl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtuqimtwqk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtqdhzljak.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtahtggrxs.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtzrtkbvpr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtxuxrxxhi.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtfkynsqdz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtnqvvxrzh.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gttdgwpinq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtncoxgmec.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtjuvlvdsg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtcyxszlrp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtghcsvvhq.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcblmirlb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtdbrwvgaa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gthmensufv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqdflalks.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtjamguegl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtrtvmgdxj.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyfyxpad.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtaoqyvicf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwycobaff.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgpyptsdz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvhtjuzd.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxktexnjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbxdyndok.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtdremivdm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxphiqcaz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtddcpwpli.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gteroopyjv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtlsjhjhed.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtulzszuda.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtdlkqpcdc.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtxiauvyzx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtdhqpyumz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtxfazqjau.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtsofdueyt.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtnkqgdplm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtqztlqgei.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtxptasppd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtvvakfhgd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtroanrnkt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmecxxmhu.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtucoglfnl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdorbueum.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtuyzuevlb.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtgurcbolw.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gtsczdjfjq.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtsmxukrez.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtukulayaz.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtiknsqrqs.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtdxqaraxs.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtfonsalhj.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtiheinlzc.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtikunlfiw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gthconrknv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtjunkwacu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtlyaoelsw.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtankzztpm.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtplxjbcfr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtaeejvzrj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtjfnzogzl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtkjgkjlou.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtuzkusnfw.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtryvrpdro.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtqbfahtyp.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtpdehegdz.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtmvegddbk.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtfydmzhux.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtlhcwotnd.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtqskbnzhd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtibbsezdn.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtobwwsroy.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtjwdndqkj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtywfoaves.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlyapfgnf.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtgxjqypxa.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtcqpsproy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtdbtpyywh.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtndrfcyxg.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gttgkwqguf.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtvxpfxtnk.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrsmkxoh.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtrdcgzkjo.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxatykxcz.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtjcfwergf.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtnpniicao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtzjnpyico.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtoeocdlzb.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbcxvibr.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnunimbg.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gtzjfzkkhc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpxvnhdhc.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtpqeaxazy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtoiwntkkt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtwwlmdirf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtiluihqnj.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtvxuuoxtg.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtcalmxvfe.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtryscypie.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzqfnqzc.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtnybafdvc.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtzlgemwfs.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtvxhzekup.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtqhkfzhwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtftjzswse.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gthefmydqb.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gticsfslzc.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtuevwyqqk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtvqqinekd.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtfxbkihqt.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gttcczmgfz.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkctywlvl.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtbanbtxld.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjimnosh.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gttkurhspk.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtskwirumd.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtjczfxbws.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxchwtjn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtqjgmblra.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtlradgxmk.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtuitmajev.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gticrbsynq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtrqckceoo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gteipbkzqf.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtfnhxhgle.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtjywpzwxz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtbppltpib.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtgbwdjyle.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtokiayvxc.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtzariiarp.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gttcxfymgl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitawhusc.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtvywsaxzv.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtylnengqw.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtrqiohjyu.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtzpslzpnn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtlbwnltte.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gthcmzivrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtkczelxjt.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtfuwtkldh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtwnfrelex.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtzpagdgrh.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtdndwkjbh.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtwillwgvq.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtmxxklpfx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtrrcgrslc.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtfvgjeuau.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtahvvlygx.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtayvwdjvu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtimgrsplz.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gthelnuflv.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtylwivpmd.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtjoyavwqj.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtgzmkjioq.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtjbmnqyii.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gteqncndrn.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtuymsatgb.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtqycdubuq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgndxkip.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtagdcmnip.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtnsfnlijs.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gthdngpguz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gtynknpnwz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtwyehdovi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtynmkrlgi.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtzoedgdjb.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttyonfplu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtpcbdhryu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gteukhvvkt.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtmlxwjgly.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtxnxoiidz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtgcwtsnbp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtnjvjfqsk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtqexeuitv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjqyemwhz.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtywqoulsb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtqcykrisy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtwuxusaka.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvcwzczj.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtnyuyapsd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtijmtljas.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtmpksxvce.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtaorrrrqn.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtxznjzkot.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtqbiurxfx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlihlofpr.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtvoafyijd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtxqorqboe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtskvvldyc.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtndldlkjl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsaylkcxe.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtrrfmrvjz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtqvihvfum.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnscajmsh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtgfztuejw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gthytobgmo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfmoupvm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtppdlnxvv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqgdltwe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtxtvttgxk.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtyxmjzgew.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtltolwfyu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtfrviujdo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtuortdgng.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtmnrorlxw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtggyqyruz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtjdircyho.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpkkwnum.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvqgavcv.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtecpovdse.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gtefsfkwae.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gttkfftkwc.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtlgcromhj.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtvfphbcno.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtkrkegwcb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtwktcumtu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtlmdxnybv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtownkmvlm.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgwsnlzp.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtrtbmkmub.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtdzwqsmjy.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtnpxnegcd.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtrhnsnorm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtgszxaymd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtuxshboiw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtuwcpdipg.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtkwtvlvtk.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtpopavoqk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gthwewromn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtvkiwuehv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtsuwdyucn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtyyvjhixs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtgancypme.html


<!-- 参考信息 -->