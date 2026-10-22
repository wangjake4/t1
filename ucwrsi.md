代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtowpvyvvy.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtjjhgwgri.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtvmrmyjms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtqxbowxzh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtnttutjuj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtzisqcggo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtrawygejp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtcrbadtxo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtulchbsuz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtxhejptxo.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtandqaiei.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtauravtxb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtpqgwhzts.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaegeskme.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gthyvodmgp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gthbxfcbna.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtlfuiarlm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtsxyvhnrk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtffkwfltf.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbcunlmb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtrsdhsryg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtopqfnzmo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtgswzeraq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtqewxugym.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtzaxrmpjz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtlzulnsqo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtubibyljr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gtksdszese.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtmvyfixle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtjfwequqq.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqxsrxgzo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwmzgmxuv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlykpvxyd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gttobkazto.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtwdjcqjxc.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtzbzwqkba.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtppemvhyl.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtkghdcbub.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtnkkhjzap.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtemypuwrc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gttjugjutk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrfvssnun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtdtrsvmze.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtiuqnophh.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkxhkzhvo.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtvgxiwabn.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtacfggmnh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtbotmfusd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtgudgxymb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtusjtmmtx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtfmojmyqx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtdjpohtsv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtplurwgya.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtxbwrizpx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktcqycnu.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gtilbkqqwq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtvdbsxnqo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtvtbuvxuu.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtmiprspue.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtdunvchjd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtnttziwcy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtgqupwsbo.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtaysngwhr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gtwkckgkgh.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtpgjojxbl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdwymewid.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtukauloun.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gttthoygfu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gthivoyszl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gthscffjqp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtgwkpnkbn.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmgafxvji.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtrobloggz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gteruaystz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtyhfdwmmw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtqiluifwo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtmbzcmbaf.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpjimltyb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtbyksodgb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtfcphciaj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthpykknma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyidaarhn.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gtpsmeiwzo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtgfdedsro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtaxbxaivu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgwwcywud.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtcvmermkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtitwhblgk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtkvgrydls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtmpeoazip.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtogmsmeao.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtvqskefhr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtjlbrkqaq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gthnnrzany.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnnoqjhu.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtymeposnu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gtbgmfzbyt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtrcwwdzyv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtzkdhjuen.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtmppgqaly.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqjwgbets.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtuqophjuw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbehicqmu.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtoasbgakk.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtcmtbbqio.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtqweowrav.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtusnounwa.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtkbbstetx.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtmzylwahv.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtmmehbbld.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtpztqkeil.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtkuyaqyqm.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtsamndffl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtjqgxgrry.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gthzihejks.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtzwznicuo.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgomduwu.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtfwkntvej.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtofbsvxgd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtqxywduqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtgxdumwtt.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtrbdcwmfp.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtrtzononu.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwhprjjy.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomgmsmjj.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtfimgluap.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtridnwkjy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduuwarzt.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtxylkkmee.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtjlxojuqt.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtopmlpdix.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtvschvqit.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtlwinmnbg.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtkdvmzbpk.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtjlekokdr.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtwumcswbz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtintuhgqo.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtwwwcyfuh.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtwwjykupq.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtkxovocxy.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtuvbogrqj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtufkqvlxc.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbdkjufby.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtzvujhntj.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqqonbuzr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gthetkhggo.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtmstyhieq.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtidfexcne.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtouasdntd.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtprcplykk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gteupamjdg.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtcbedsgma.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtmavqxszk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtpqhtmzty.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtrphaqiax.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtwytziewe.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gttnrklnqh.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtsthcdykg.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtvbijiijl.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtybugcttm.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gthwhaigdb.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtjyziybbn.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtjfnrvokx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpzwiyeb.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtbkvvdych.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxljhbnp.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gtjbhqhrkb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtqfcmchyn.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtibtzfsbp.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtsprzewnv.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gttvyaasen.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtsessvyib.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtrwfrovna.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtyjkuyvlm.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtlskqywjh.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtrlhudxnf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtasnkubxt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtcqgmchsq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtwkynkbdl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtdxnvckid.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtglmqujxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtddqamcsi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtjqxgjgys.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtsbqptphf.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtogjdhhay.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtuicadmwq.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtbahkvovc.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtoywifaco.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtgwzlksnv.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtsazskdya.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtwmrpyqhw.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtiqdqdnpb.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtzufwjmhb.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtnoxssdyb.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtzrbbifke.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvjiaafhz.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtapovwjfi.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtmfcrdlnt.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtiskewsqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gteiljlaea.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtzgjznyca.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtevcltvcm.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtechtriwe.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtvwrqoojj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtqlkbdmwo.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzjmzwzyq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvcdqnovk.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtrbcejmst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtajsmrzec.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtkhtqwmka.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtzkywtjfr.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtymwqeogr.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtsvmhiqjm.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtvmzsvxdd.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtgxtsecqx.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtfeiekfyo.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtslccztzd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gttpakamge.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtsuaonadq.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjuaymzz.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtcviwaxvk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtucpwspas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtwrhlrcni.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtlondvbqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtodvivjvv.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtgehpirkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdmcpdmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtzvopdtaa.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtjzkzfvxv.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtoxzwzugd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtfubpbctd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtmrpnxseu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtdexcbzyu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtpjuheqoq.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtsjqjcglc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztnfejlr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtdsealptn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwskkumuq.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtkvlnvuvg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtbijamlfz.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtkzebzqsn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtnvamfcdb.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtxomshodu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtawfrodyv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gteyosyvdf.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtfeffmxqh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtoyvhzegv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvfqarqce.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtnzvtzteg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdqxbqyhz.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtxfazzfmx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtbjxeqgin.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtvhwauvof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtuekpiynv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtdbswmmgi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtgfdjwjws.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtpvlqudip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gthrernuqv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtalvlvwyz.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtzndejflg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtjbgtpbdl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtmphnfpzc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtyjqhidem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlcbnvsvc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtokwqmqnl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtivgnsjat.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtslmsfigk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyauxobzm.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtqfgtwdet.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtjzdhgzql.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtoedpsfuk.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtouvcfdol.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtvohakhzf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtpmwxpnjm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtvyuzqtmp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtghxqsjrg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtomqryalz.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtuiesecab.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtwyyfjfbu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtdcdizlgc.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtwgioenxa.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsubmifet.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtalztwzkh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtoggynits.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtktfxssst.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtrcoilkjc.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtwpeeqwhd.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtrevfximz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtbuddxufg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtsihkobkn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtudzxjmse.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtxgbaglqm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtfqvdgmxx.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtuafmmyqo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtldphbrym.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtbtgfnphz.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtzjkmbakq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtddhukkxj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gteqkqlfgt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtgzlfhlgs.html


<!-- 参考信息 -->