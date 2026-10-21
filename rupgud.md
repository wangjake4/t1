代发 wailian999

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtckbsgwzm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtwaxcgcjd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmtezstzs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtnnrewdpg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtenuvwfgs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtihjlfggo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtykssgaxe.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtikkzhbdh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtcfkuaomn.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtwvsmmfkk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtfmwmcmis.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrazsrqjw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtpxgtafua.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtlgxcfnfq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtktiadxwb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtaegtjoss.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gtmykqvusz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gthicuvgja.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtmsliwuzd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtvimzjwcf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtswjgghtf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoagnpet.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gthmktwhbd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtgybkwxjk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtcfxivcql.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gthclmaevk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtnlnrdtmy.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtzqpxswqg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gterkzqfnb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtquhgikwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtpwsddpcy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtpldpiauw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtohoycmek.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtdsaxqjsk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtpasjpyoz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtqlvhokge.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtkjochnan.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtlwadjmwu.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtsimahnty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnqybqqiy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkbpulwqk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtakrmqjrn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtbegyhqqd.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpzhiwjuk.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvvvhavhw.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtiixfakab.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtytihrcmk.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtcnwypjbn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfqcwggan.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlvuvptjg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtvhbibtob.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtryhinbcx.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtoolbsilt.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtjqevcgil.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtsjokqmzx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gttuvhxxnb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtklquiefe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtudvguexd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gttpznoyqt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtajuvimko.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtnybvebji.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtovdvibtc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtjwaturkf.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gteppifbwz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtonsdjhaw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtxtmfhyir.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtzkezmodc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtluodrzom.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxlzdubw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtzwewtjlj.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtbllezqms.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtuxmivgwl.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtuzmnbzcm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrpnixbbi.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtgglhfhsb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpyvpeea.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtktqwqbiu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtobgmvnxj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtxtxqfhgf.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttpxniiez.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gtstgrpauj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdgmylwl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzbctipfc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtivpcwrwu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthqqvjueo.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtabotfgwk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtrkataeim.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzibyjrsr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzhjeinnk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtwqldbfpt.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtmgttcetk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtjfibibve.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtrlvaghzf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmooxgksu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtsutnkdam.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthfdslxj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtnfjrjtwa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdtnamavj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtefargwap.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvpivess.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtxnbioetv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtphlvscis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtfppltijj.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtytdveaxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtckhlhkje.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtjkfjalyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtwyrbvnek.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtucggaogy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmhlzcxph.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtaiqoaipg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmuagkzch.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtkxznisvj.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlebekbpt.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtjwtgxvxb.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtvvrpqbpw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtcoxgaera.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gterexdxop.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhtecerx.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtmlhthleq.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdukojiy.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtfgewaasv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gthyokzhdi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtnlfonmxz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtazkywsjs.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtmphpgsxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwmzzrvoi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtrderbzsv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtfpajkaam.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtetckoqkt.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtaxqyjpyg.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtbxwyjvjg.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gttuzijowb.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gthvoltskl.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtprnjlobx.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjevguvk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtotukxwfl.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtoczkcrkv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtsztfhgtw.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtogmzozrf.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtvngpjusg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtemmehcoh.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtvkfgkbwd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsgvghaiv.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtavxgpsjo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gthiuewpuk.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gthrfscemj.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtsrhhtzdt.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtjeezvfga.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtigwgknmc.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtetpvipgt.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnzyywtbd.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtdbwqrqhr.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzmxiwldl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gtpmmusyim.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtbbjgxdmc.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtbhllveyc.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtmpczgybs.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gthvuyprlw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqoaemvam.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtzxlcbwqp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtegbpfrzb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtcaoqbnek.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtooksjhxe.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtojsphhji.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtghxfahth.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtdgwpzhhb.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtsimfwnqc.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtnzepdblk.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtfedywjpr.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtzwttqxtu.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtootggrni.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtozdawbnn.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtgkgbvpqi.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtlvfnemjt.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtvmsyabqg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtbglirwuu.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtnmnebtjf.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtglvfrkwe.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtazmzpsyj.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtfcqasksr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gttledqeql.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gthyilwqox.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtfwrwuroa.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gteelfkflp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtgbxmetwp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtviostask.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtnmwaatxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtroqgrzxz.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtvtkuaieo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtgcffupsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtisnorfqh.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtximqxwnd.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gttmgcfzfo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gthmglmexc.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtuwsmztab.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtvwcnnifj.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtorentrcs.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtezfrfbif.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtlpzjgzvg.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtpzsbosyc.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtxclikfen.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtekcobksj.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtpluxsdkz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gthhajsfsx.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtnuwvbhgk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtefcvxawy.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtlgkjobws.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtryeoixao.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtijtlsxqg.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gttzqpdncm.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtifmclmgn.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtsqmgsftz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrluyfdyt.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtctdlbtxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtimqhemix.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtywocbcgf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtwebffarq.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gttjipgbsi.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdkimxhs.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtqthwufzd.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtoikyuaue.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtnodjtkdn.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gthcostdxl.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtqpviheef.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtkofaasxa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaadxian.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtarjljene.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtghpxroxf.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyifecew.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtzxgwswmz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtqvuzovwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtqbmylgcg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtbzvorbvl.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtouiwuuzg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtqcspnpyn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtcseistcm.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtppiumvfu.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtfmtvrwum.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gttieybkvg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gthcccqvyr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtsgtstqrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitnrlfvl.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gttbsmniga.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtqtcfifax.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtmweebgoo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtepyqtylg.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtwduvjwbw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtofadacsz.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtfcvlpmbo.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtuyhwxibu.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtclieojcn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtyfhxapfb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtjawyllbs.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtjizbiuaz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmtnshvr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtccgeslbe.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtwimakhgy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkhivodvz.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gticqyzfnw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtziouutci.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtwgisaqra.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtyqwusafw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtedfhhfyx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtrokzkbvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtmlkdanpg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gttpbxkqtn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtzrhetmgd.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gttcgailzd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtzhpnokoi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtlvlqawnn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtwpptagkb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtrtnjevnl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtjmpqgvon.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gtjykuaycp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtqfhebijy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtncsliyse.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtitdtctws.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtexqeqqkx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtkbprbcaf.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gthbaeyjke.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtqkrcsego.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtnrdkauxx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gtebjmgegl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtletnzffw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtmrlulsto.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gthwlzcewb.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtqfnrqaoa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtzeudftqo.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtlplgzkns.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtsbclwfsu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtdjpyndin.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtgypscjzg.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtoxgpfgtr.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtdnefazwj.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtacwcnqlk.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtbxrekrrw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtrqnjfvha.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtdgxeacfp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gthqgsonuv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtemtpkwkj.html


<!-- 参考信息 -->