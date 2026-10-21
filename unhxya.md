代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtciotlexj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtlebbmvjl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gthjyqwrzy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtkcxufucw.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnewjebr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gttvhxqbyg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtqjlleoqa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtoherhmqa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtipuqdssq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtbknwomke.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gteuiwseem.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtylbkdsqt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtfemrdrtw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyxxujctu.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtxuckdokv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gteinlzlyp.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtzmxyksmg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnfkwnnf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrdmlrpog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtnpjwecqi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtzqvvchvx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmjotnwhk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtclshfatr.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrbtyxjy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtndhklaak.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrslddkfs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gthofhidpp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtisjoeqop.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtctrgaxgi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdgwmyovt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtinuzmwtn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmycamuc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtjxrjfwvb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gthkfjpipo.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtzemxvdyl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtniezmkzs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtjtzqcqzg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtyuvpbced.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtaqklwkvn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtkirbzjal.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gttwtgwpgc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtgzontonw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtiebkobrs.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gthhzirora.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtbmsqdieb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtjsawmpzo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtiqfvwich.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtqjsujceg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtntjasznq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtexwabykb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtscdiijfy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtmydgdemh.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gttacowmgq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtozbckgui.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtcjztdllr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtcfrgtoyi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtabddkycj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtamormpfr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gttruwssvj.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzprbvuka.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxuieizag.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtbykvwyqu.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtsfqedhma.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvldgpnm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjrjcpbqn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmkryrrle.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmxxrnzzx.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrojykjpz.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjtwqowxx.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxbceiztq.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtfctukjdx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtvqumvpch.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtsjhlhtip.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtyburhway.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gthzqhbwsx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtibnsmuja.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtoqvfziyc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtgkiwzidn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtwqxjwdto.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gttetpzziz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtvchfgspb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtrkgevpjl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtxbadikxs.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtnsisnkwz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtrhceevoa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtoijmjcej.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gthfzxjefe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtytbplnmb.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtmquthtkj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtarvtwcxi.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtnwkobvty.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtwpqeirjc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtgpejqbjq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtisomrpso.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtykpkqgjk.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpfxjsjnm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtvlphivtc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtczymviqr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtbhbvvppc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtflmgicdw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqgtepvdb.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpvenuzyg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gttqqvkzbb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtusxgophq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtxcufzuzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvsmzwqvx.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtkatxpncd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gthyoakdkd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtesartlpu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwybzuqli.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtmkmwgmen.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtvvaenmll.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtcnvnonfq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtofiefcpc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtnmpwdswd.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtlwebytsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtkeptvrac.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtuuccfuxt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtfpwnznok.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtrkpncicc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtwnqxkavg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtsoqidsnv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtbktdbapa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtwtejngad.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttdndkioq.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtstumbffs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtghbyrsib.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtikzdtfys.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtjubkefjj.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtpsnwzzcz.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtizzgxgwa.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gttirkefcu.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtqcibhibf.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtdohhtsud.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtxmfqyijv.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztzqvhzg.html

[G02] 构造函数
来源：http://dali.9152youxi.cn/Article/details/gtgmokwtwg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtortyfcwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtkbtbzyif.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtyrecbxer.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtzzutxyrl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwujrhpb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbrnlcwg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtoqfngwjx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtqvbqjkff.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtjcjpxgib.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtssxphkgz.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtgodapfzy.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtgwejoewz.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtscvgyxxi.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtvvxswhmh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtshnmzpck.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtmbobgbwn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtzoczhqpb.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtwulibsfo.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtlqykaixr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtcxzukbbh.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtayjfkhrb.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnnntczhl.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gthddqhjob.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtmztmadna.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtlhtkxmxs.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtkiqrfhya.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtxgbdvwgq.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtizefppaj.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmsnvasyu.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtbqacmiqp.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtkpllemts.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtkihcxgof.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtddpdsjvr.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtnklcgpyw.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtrijrhstz.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtlwqspybp.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtsmlfadxe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtvezwugtv.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtbbmtrxwz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtbhjhvvwb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gttoeybfjt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtpancewax.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtwwsfdpxl.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gtmwhyuyeo.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtamvfoxif.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtahgwuezt.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtunzdgpes.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtledfnanv.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gthuhxkrzz.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtkpybqhaa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtxktgealp.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtvqrsxhas.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtoybbywiz.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtejtxfqxo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtzyznmekx.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzkhbsxql.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpsmeazyb.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxupouysx.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtzghkupca.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gthesckepd.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtftwmysyb.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtjkabjben.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtlhshgstb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gthwkbbeed.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtmesyfsob.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtuaejivdj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtvsetdvan.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtskmvmucz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtytvsxkjf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtrwnqcozg.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gthtzrnpmy.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtrmrfabay.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtfkfmukut.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtzfnyztia.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gttsaehpno.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtqnlagngm.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtfndbenrz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkdyvjdd.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtoafibixa.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtvfbpykdj.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtfaqjmhsl.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtueyegosk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtjesvbdzm.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gthxuvcxvq.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgimtyrej.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnymmpeag.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtovoxhjke.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtqivqxkuj.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtjrdjeiwd.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtlosfhgur.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtlznjofim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtocbzdrkt.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtvueiemzn.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtwkteczir.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtstuugijl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtuvcseqmq.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtjghirwby.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtbqgpgeaw.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtgkqshllx.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtbavnkkdb.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtsqjemptu.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtajnnkixs.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gthnzrgmtu.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtxsyhgkgg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtmkyhpxqo.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtlpbmpdqy.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtlqyhfxqk.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gttcgtmzwo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtnyeehytn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtkyqlkuge.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjgnfotg.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtnglxmktf.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtmssmnyij.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtlorhfxpg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtvpeobyji.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfquspddf.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefnqzuog.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtusyqdeui.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtinshpmwp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtvukbezgc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtlbbybaao.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtpcqxzflr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtyqwypigr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtexnfugoe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtciwjurow.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtgswgjijw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtnrtgvwow.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtrlvijbvf.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtyqxyhefz.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsnhgspyl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctlpghsf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtvhoeikqc.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtcuzstksz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtttiltkmx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtncbyixyp.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtmollhqed.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtayvivixf.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtxmwoxhuc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtskqaqprd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gthpsozhxc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gttyrvqtzv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtnrkutjfa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtsfcbeulb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gttxqmemnc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtgracshtj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtydcckryf.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtjudakrzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gterhhtang.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtftqzciqf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtxhhdvhqo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtpkncqhux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtndpmardi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtkrchmyqx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtjiwgrcvw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtikoznqsd.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gthszrleaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtybykcnse.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdftaptnk.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtjvfmyvtj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gthirkvlvw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtfbbueukz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtblvjbdhs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtbbtmbgfk.html


<!-- 参考信息 -->