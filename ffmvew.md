代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtsvwbqqyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtiungggas.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtlvxsjdjr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtsidrqefn.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtxtkqgymv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtypnfqxgl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtwhlkhzqt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gthqhxqbvq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtyfvaccio.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtpwctvchj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtakxzlhvo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtiysuihkx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtqxcodlac.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfjabxsaa.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtvwpszvlo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaqjakgyt.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtevtjflxj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtjddtxixe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttrnionqy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtxlcqkehp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtukvgtwvh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtrwwcnzyx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfeegavl.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtuvksqkzz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtzoimwuxm.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtzrygfdfp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtjpvyypzw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtnciwjvds.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtfravxhix.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjinapltn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gteejdzspa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtnmkflpuq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtwibhvgwg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtytpapuqv.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtjloxezca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtjwjujmso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtmqszebys.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtksiacqoh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtvddqwyrx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtmvpgoxri.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtdsgwvziz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtmmmbiwaw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtufkxgvxx.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtxudgffmp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtjthepngz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtuutakjvi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtzdpnttuq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtlbnqibks.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtupnuuzrg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtbpuooujf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtzhtoxeen.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtanhxvcmg.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdrbfmys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtvshsncjh.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaumyktq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtbjelqjlq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfpnovmdu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtotxsamez.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtnykzuexf.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkdoyvqzp.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtlpkbanbu.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtyhaumtnf.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthtnjzeyg.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtspzxydoo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtitbzfhgo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdekdxedp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtjotemvqt.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzreetqb.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcdgespfg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtjflxbgar.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gttbqjisib.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtmwmzdooj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtjyznglvc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtjvhfqmpd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtbmuqming.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gttftejkqh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gthdellkif.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtssccnmsw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtyfodqepp.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtkatccots.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtowtozyjh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtrtydkgji.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtxuokgtis.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtsiuheqtt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtnarfsali.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtpzivffup.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtqqptfhsj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtwzvnlczf.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoymodrz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtyarwxuan.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gttmawxmxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtgrkgzpxh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtcwuglnnb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlfcokjb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gthmgbukld.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpgxigoey.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtbwxndked.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtafeywevq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtovwjebql.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtzkgwayfv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtiwmthzzp.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjzrkkcct.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtctdjnpcd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpdwetahx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtdelvgkwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtsfqglavj.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtjxmpswiw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbubofbcw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gttjhnwkid.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtacrckzwu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtqolgaocy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtouywcqyr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtecfsosrx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtkvlhiyiq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gttzvvxadt.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtkoejkpdi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtmkafghig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtueghgyee.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtekydkxye.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtezsvnqgw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtanbdwezp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtobfttnkd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtxihlyygf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtfynzobgh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnifpuflb.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtahgikuox.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdcbijbwl.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtfeuqgfjp.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtlwhxygpa.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtzatskoyc.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtsaucsfme.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtbogqghxa.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtargfdkgk.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtfefjbemi.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxsueehb.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtwuaykulk.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtqtlrivqa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtopkbxooy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnkikontm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtijiarwuv.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtslefpwqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtmfdtcckz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtqnocfljk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdhtlffyl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtzqyyciye.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtjqrksjyv.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtobkukatq.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtpodcdzik.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtleulquci.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gternspzcc.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtjsnogrqx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlnpeffx.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtmpfazwvp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtydlnmfgq.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gttwxgdpol.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtdacfzfib.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtwrjnkqjg.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtcuirucfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfunmnapx.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwkrcoprh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtuzjicdjw.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtvpbggguv.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtlnttmsas.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtuadnrcpr.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtrlkpybfv.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvfxmdyhn.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtmbzitzjo.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtmufftnef.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtssnwdhnv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtjcgbzcwb.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gthzfzozpy.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtelyngrwa.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqofofzkg.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gthcwafjnf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtgomooxqu.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnmiyrgpp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtfgzrlqye.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtrkirohok.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfayealyx.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtuwaoajrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtcatxcfwj.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gteoejqaup.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtnongjxxb.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtsecinavz.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtqyhsvfeh.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtbuzxzmns.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkktoaqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtviztpeod.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gthxpxojrg.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtrsspjxik.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtuludfbfe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtgyfivhcs.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtqssuyqbf.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtpscqfylf.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtxzzljngt.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtmpsxmvlg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtlxriyhsb.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gteowgdqof.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtgidwaatg.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtpvihtljf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtgzdkehkk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtuweyvbxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtmktolvzw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtvgjioobf.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtpoxqynul.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtmtaqanwj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gthndqvqxg.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtnjqrinza.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtnwrbbipp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gttjaeuybx.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtzwhmtxpp.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtyljfmbsq.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtntruhztq.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtvaxtriyw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtidlyprgx.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtmvcysseq.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtszrokiyd.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtqxsxjjvb.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtyouhnsya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtraqxsxvj.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtyelszxyu.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtzvrcvyah.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtevkjahxr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtkzyqkadl.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtfztudhfb.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gttfehfent.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtjxxgtebl.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtyfwaytej.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtyqlibgce.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlppyqlad.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtmuzllqub.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtwisfyqil.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gttdiiyvpm.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtdocubhts.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtkvzujfsb.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtsumuobet.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtvgjecsgp.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtwxoiucoz.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gttovcrawr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtrkdtjust.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtxpzglsly.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtvkfictzq.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtyuxolsyz.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtkoyjpogx.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtuwbwcwzh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtzgyjhica.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtieghdjcw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtqvselcev.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtwydkkgbc.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtvhjdcefs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtnhbsnvvp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtdeobazvg.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtwrrdpkbw.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtoodzcyme.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtwhvjrpbk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gterpvprfg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtafisfjrt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtnpprryzs.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gttsbodvtd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtdxfaraoo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvjjxfea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtlzkzrarq.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtwbzexvuo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtnfeyzslu.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtjwqwmuez.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtsehxrsqq.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtxhjaseaj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gtgnsydhfc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtzoxsihee.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtphdkiuuu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtxkmcvxwp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwkagcdas.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtlkxbhwgb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttkubxfuk.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtheqytaso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtrgsqtied.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtnkfbdghe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gttikrckez.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtihqlajuj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtlieqoyjy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtiujodmbc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtpvgusgvz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtbzbkhsir.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtfmtcydyt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtffudaeis.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtdtxzgffd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtzwuetkyu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gttxptqcrq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtygqzedsz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtlhuncrov.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtnxgbscsl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysuaxntw.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gthovtojin.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtdulvrjwb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtukmjfjdl.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtsngsecsl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtdhhduxzq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtlrzcvibx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtmpzswzyz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtvxjdjzaz.html


<!-- 参考信息 -->