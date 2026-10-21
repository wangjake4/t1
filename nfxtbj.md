代发 wailian999

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtgvpmwoso.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gthshfpheb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtegqrvynp.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtiqhxruma.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtgbguazfa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtutigpzgr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtzbwkgnge.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtsugqopuy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtxrnndwzz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtznouavij.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqtnloog.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtgzqfcslv.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gteptsednj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gthtqomfoa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtfkkbtdnk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtqvdimeps.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtnvrjidjj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtdzaztych.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtjyeicdjs.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtezfiwkbc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtrnjctdbb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlpkjhzkm.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtodoeuqrr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjvridnyk.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtkpruonbw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtwlnlydpf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtusgvzkwv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gthwrxtzes.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsktrdiu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtgrzszjqn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtgbbwzmhw.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtympebcqe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtitobprmv.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtnwtcrfww.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gtxihlspdy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtkawcymio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtbypgsaum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbmdbiapx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtdpoptles.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtarzffmnj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtsnvtakbf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtyioncvrd.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtgoeuekza.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gticwemwph.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtvvavylgy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gthrhifrgr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gthypkezem.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezircznt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtpsrqriql.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksibiame.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtruaiwoti.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtcehmgvlk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtmmmmykxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtrkbmuhtn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtevinpupa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtfqkutrpb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtowwcgxbs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtyngelnpm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtiwhromqr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtclcokbho.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gtnvxgkuro.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtypxhkxek.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtinrbnmrv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtovicvuvo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxfhdnlqz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gttslmcrlm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtubxlyceo.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvizkdoel.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpbwccpio.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtkbugsxnm.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsepuoiil.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtddbjvgmt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrvjmkees.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnfpwtmlz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtisojcpuv.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjrqxsgpk.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcwqvbrvz.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrbfgnvo.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtdbkkxkne.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtaqpbgzxh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gteojewqdp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtyxbdbaye.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudmsqexx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtajczspfc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtdfzrkjsm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtnxxfusij.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtvjqbzfkt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtnpupbacd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtchlooieh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtxruidrxi.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtrahuscge.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtgvgekqfp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtejyowvtd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtnvkrhabs.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtabhnmyct.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtpqsixees.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtbmhnlrjq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtkdftivuy.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtdjqmhrmf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtbjhguhcz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtclshapog.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtcuuzfvfb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtyfhuaido.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtekdaqsty.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcllstrdb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkejpigug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfgktrpk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gttysgvtbr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthkymjvlq.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbhmxetya.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtceleeuxg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxohhgews.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwpogkgnu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtoogjwxbk.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtqrhiyntc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtosgfeuvp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtlgdypmsl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtilfquvzw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfxeffurc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gthjdyxfar.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gttkoaoxwp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtjtuuhmev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtjofrdmag.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtpbutkchw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtieqmizzb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtshdfmnre.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gthvksojhg.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtnrodxudc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtblewoajh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtjptnvkuw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtvtmzwqfd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtqohldocw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtydxjfiqk.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gttkwzwqnj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkqqwodtc.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtckoktuoo.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtpwxmfgbq.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpyxcxwh.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtwpfqvsjs.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtxqxwktbp.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtsvwefydr.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtnwzaofud.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtnunttwbs.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtnfubohtc.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtsmpuvwjh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtqrqrljlm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzdkolits.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtwsonyuwh.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtoaaxxoxr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsosxurhy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtbvspwknj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlhecddt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtjnduwdcu.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtjeplrwmf.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtsuxtfsia.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtkwzdmwiw.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtckonkauf.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtwynuxrqu.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtyoofdgdp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtddjmrkzo.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtmnslnlnz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtlcpocxyw.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtibonjyac.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtcmtaqbvp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkewlyqnm.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtbznlkfyh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtmfpqxlfh.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtyxruizof.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtnmjadagd.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtkattkwpq.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gthzrqfiba.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtpoiqkwle.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtafplplxk.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtnqkrbosa.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtwwqipyha.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtyshrmuyl.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtszwuusxz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtrzobqtas.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtttehbquo.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtawsvpwss.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtwmijarxz.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtphpmrqzg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gttxeblmyp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gthklysbps.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtimjvqpde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtalnrcojr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtozytgrvv.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtunfbdyga.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtmqcnrrvn.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtwpkrtlbu.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtpcnsocjq.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtwaetykqo.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gteneqwigt.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtunavisjv.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtebqehadf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gttodperad.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gteylcbver.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtyozljcrv.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtwzimusoh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtszhlcsdg.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtyyeatoqz.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtfzjfyiaj.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gttzdfgxyh.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtbjaspzfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtnqgvszcz.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtbohpksgm.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gttlslcmuj.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtxmupfhgc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gtzpmncwxu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtacigceye.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gttentdqgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtdwqudwbk.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtxorubdvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtfvnavhzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtnowacxin.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtfjcfxlln.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtpdpugcbq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtgnolbgif.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtsgmxqhuz.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtkgamrfnf.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtjxjrmboe.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtsamdctbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtxkrmersx.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtfffwbxpz.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtbfuqnwwh.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtsnteovfm.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtwutlekev.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtuntetsem.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtuejvvdyo.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gttzqqjtcb.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtdedvbxru.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtsthlocfx.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtnwqwbgmn.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gternghngl.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtguaxered.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtzspsfcwk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtydnqzjwx.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjwkflnek.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggxswgnt.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtseppihqv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtixdpwmkv.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtfvgrbkaw.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtvepcjcts.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkxmnxui.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtmlesrmet.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeatzsek.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtsvgpnpmz.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtrmaxencm.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrzpspmdn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gthdetpntt.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmefrzuna.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtigqiuysb.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtojguysma.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtdnzwsrcy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtmdvebdsz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtvjrgvnqe.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtjpckcden.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtmfuqcmkb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtbhoezevf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtdgrjloln.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtsqdvgxvn.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtxpdtugzc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtrdevwxsj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwqwgyifm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtgchtbmzp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtlgypivnn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtvwrsbctr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtoopmexqy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtgbllkcmf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtppvhrxtm.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtbpmmmjpn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtknfjsnhb.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtbqqogtpi.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtlhphjcra.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gteyeipvmy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gttpflqkua.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtgxguqhss.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtraonsmak.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtgatkzhnt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqhkxftbb.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrplfokjl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkncrtiid.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gtikoigghy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtjcbtwftf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gthsjajpmt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtlarzcosb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtklmueihl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtnncdunrz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtfqhdallb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtwegajhsn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtvisvubyv.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtnvamzvca.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtncthvpef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtkvllkqci.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtnptotwwh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjwziobjl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gthpckeseg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gthltjnjhq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtgaypdspj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtesrapwgh.html


<!-- 参考信息 -->