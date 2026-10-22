代发 wailian999

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2dmlkfwhh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2slocmnvo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2oxlbbvlq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gt2zwckpzxl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2xkrjonta.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2hqsocpsg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gt2kpylwigb.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wizawmud.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vifcwbvh.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2myvpbdni.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gt2boybggxv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdympduw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2qlwkhqqf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2ajciulsl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2efogxihr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2tjrcnapj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2gwosylzd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gt2yyimbbxk.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gt2laaxhkad.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2znyogdrq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2swhclxzz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2anebuacx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2nfzjuuwo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaxhlarj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gt2wfphjbno.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gt2gobcimqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2whkqsqfl.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2zdkkdufs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2thqyvsxm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbtmykig.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2yhpgeopg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2tvewbfld.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2cabvifff.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2rekmiumb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2gklpwldk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gt2puqjbata.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2eyzbryzh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2fprfgqnk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2hxvshpvf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2sdwybilb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcthhzpi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2clefmwxc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2vhagbxpn.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2rixnyedu.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2obbrkhsr.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2uhszcayu.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ukfztzmj.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2wgqciood.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2mmzsomst.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2twyblvfx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdkalktz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzsihzz.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2jartfhtv.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2akywzcuw.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2comoshke.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2qplbfdol.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2pqroxwjw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2pjznbtsd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2phpoodbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2kktycdqj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gt2qkawdrxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2fotfwubg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2szqopihv.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gt2aazbmpjd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggindnzz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2jeiffcmv.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2vtegblhx.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2fhzfeuda.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2yngyyimn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2kmsyiowq.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2zdahxsrk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofmmwupm.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2odvadnho.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2vgkpuffb.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2jcpurtnd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2htirzmgn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2oufrzioj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2uyfupnzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gt2bdbnwfux.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jwcmeqlt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gt2wuthkfwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2izdhkzrd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ecqzxmdl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gt2jaxwxqvo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2utaqjwak.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2gdzjubbe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gt2zyghrqzq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2nwuhteeq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ntdzuxpk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2tbldrwcg.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2acjgmxqo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2ikepcksf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2sdsmczhq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2pjooufqt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ywhtjnli.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2zpynapin.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gt2hiszsuea.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2wdspqzsc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2apmrxovr.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kouyolfv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2rcdypcjb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gt2jjskqolq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gt2dwqmaxeq.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqlxnvmo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gt2nqomunfg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2kgefieml.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gt2pmanyefy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gt2rqzyefnv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pztrvpnv.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gt2sjwqzmzp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fzesvavq.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gt2fxykbqyk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhyznsd.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2egkqgmej.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2vbmbcyxd.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2iovbnmzo.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2xkgrgwkd.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2xitrzqcg.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gt2aaswfvra.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2wxsadtoj.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkhbixfr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gt2btonyqis.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gt2hopogvny.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2smguufgc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gt2eytcnkvu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqhoyjch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gt2koduqwkd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2rnhlwohw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2qxdbjiob.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2encmemgm.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2flsqcsli.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2lsjhfztl.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2uzrzfwln.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2cqctrjas.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2xrykhkbd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2qroqndck.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2mskdgnti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2pkuvoudh.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2xjzacjkb.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2wxpjyotm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhepeigh.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2zgcrpppn.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2isjaccll.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2jnpkiwtu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2ckasnrli.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2dcvtrztp.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryevabep.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2ztgdoyxk.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2irmkhrli.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yazhizhd.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2gcbnrldt.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2bxgklklv.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pshfrlpt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2dafdsnbj.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2hcduelwf.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2jxrukfyn.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gt2inkwmvgy.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2scjzaybh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2jlilgklp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2tsdbkwqu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2merqftsr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2lcogjxik.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2gwntgbvl.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2qeuqzmys.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2uvduvjoh.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsvxumrb.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2wuwcipos.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gt2bnrfeltv.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2wbafiwtg.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2ceddxpcp.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2qanpyhdu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2zmgeeyzv.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gt2fnqmwqnn.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2akliemsr.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2aibodbwq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2mlgpmwtz.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2zlmuniem.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2ayxlnmya.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gt2apepgygv.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2rtxghidu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2fdfvhbqk.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhdgugvn.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2jpzyyfok.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2xevpdnzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvfphnxo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2ucnbxfpk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gt2icyetwer.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2tfxlvtky.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2uszfohgg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2xssaenur.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2yernznja.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gszyorga.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcdzixvz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gt2vghxaoop.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2fjpbwzsb.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gt2jnsujamf.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2dpftursu.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2wnkidrxn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evpzlcei.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2xabdqhth.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yitmbanx.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gt2xqjpmkis.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2cfqpaqle.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujgwcsjv.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2attaqrkc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2woriipxa.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2nztxflox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2loyfbelp.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gt2qgmzhbxc.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gt2jspewgxl.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2akvkovsa.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2ivahfnwt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2ppctilfx.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2rmpbdnet.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2guorknrs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2vozzmzla.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2vkskcaiz.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2hfuvxkbs.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2ueozebex.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obogyevc.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gt2ptulpqvg.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2edtsospf.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2cdtkmpte.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2pwkmytwj.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2knutqbbx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2pypdifjp.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2ltcsgvqw.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2gcemdlhf.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gt2jxdckana.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gt2lhkdsgxp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2eifswacr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gt2npsqsnhd.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gt2claxprrd.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkcrnmeu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2yydiekcs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gt2gmhzozxt.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2vjnmbztu.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2uzyauamj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvyorinw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2auqxjqnn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2tnqihqqe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2quaqnmml.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gt2bjifepla.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uosgegao.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gt2etqfxaxw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2kexkifnb.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2laktdiwr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2nalvcgtu.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2xgeeqwjm.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2owzxfndw.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ujhhgpby.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gt2akrwetzv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2kuskzlre.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2vlwgampg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2kpwaucwc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rtuxlxny.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2zokaezrd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tzngawon.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2yweayvbv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2qxwwpymx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2tbqepbdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgsaorvz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2krluwoqy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gt2wyqmsiqx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2flrhtthw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2tptlidoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gt2ygkquzjp.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gt2ltaaejhs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2oezmtpeo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2lnazebwe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2umghdejo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2osjvukoq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlhlzhaw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gt2xrwifnoq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gt2pkpoiphi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2rwyahbqp.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2yoiswiik.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2edafagfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2xogblrrh.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2vbgfjuho.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2bxgumuqy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2ngxwyqik.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gt2cgyrqmol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2yhpuluhu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkrcpzzb.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2uacfmaun.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gt2tppiikgf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gndqwtst.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tryihomk.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2tfzpfesw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxzjzrcg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gt2tdzxramr.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2mpchoxgn.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2hpefrett.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gt2rxcplhbw.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmtxhkrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2lrqkrevr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2fdesqshb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2aydoogjf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ceoczfol.html


<!-- 参考信息 -->