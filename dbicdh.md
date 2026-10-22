代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtwjfgvudg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtoiloumfu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtcyoywgwn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtjnlpyvvb.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtrbgmhacq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtqpdvltqm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtmnakxhji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtntqnlhxa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gttqojtdhs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtlpxbrvhl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtbjzrqgcx.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtrvlwjhkq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtmmgfboud.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttgehbuip.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtzalkpmzg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmxrdqpv.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtntgeznyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gthwcobnrf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtyadmejac.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtdmduhoai.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtvywofdtf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gthokgueke.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtxzvnzqvi.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtngaakzho.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtaxbrbobu.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtblsgrqym.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gttpnclpna.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtncqroydb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtrlfkgowz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gthudenibm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtjwlbethp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtbabgzsgy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtovnrxjxs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtpuhmoirh.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtuzyhhynj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqqxbdpc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtlmmbjdud.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtztlxogmq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtfsitztdk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtfcwujnzg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtjbxlaokn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gthakzcton.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtxufrinwf.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuclasfmu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtilhgcajk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtjgiozbme.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtlfciweaa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtszgmvtzn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtztclgtwj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtwlxibdcq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtdkmpjvxn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtooqhlcrd.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtwkhmijrd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtootkucjf.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtomagxdac.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtufrgmfem.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthmsfyyzl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gthbtthhvr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzevhvke.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthdbfwruq.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxoxnlrj.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtecycowdg.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsvleruls.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtoajzaaqv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtnaobobmc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtyicpswmw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtbicuwrvo.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzgvgszcn.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgmjefhfs.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtbeulfazn.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtivwitqdd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtkxarwala.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtlshtlocw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtftzpkcro.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtciaudjih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gtjrdnwqdd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtyqmvzpvk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtztpcivol.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtdyrtmyqf.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtkfddrcbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtyhpyylfe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtcxhoqpvz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtzkuyyrky.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtznbxgztd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtaxfghvuj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gtfejflkpm.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtdbnupxsl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtthkeiljp.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtfcuuwohf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtokdzpxfb.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgsiougz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gttsgqrvty.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrupurgub.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvpfhryp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtlugqmjvw.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtrehvotom.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtbzhlmipa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtitxkifan.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxwyeppwb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtoeqxwopk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtuxmbknbx.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtoytktshu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtdphshnzw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtiwzsydzz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtqqqjqjry.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfccxfrqe.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gttddleepn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmezawzws.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtugqvwgwk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdgmrwjpr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtycvjdiem.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtlhvtnlub.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzznhvxd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gthluensdn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtjypuymfk.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtporfclci.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gttoefugdf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtklzdiklv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtlpxanipq.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtxnxcshdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtdscxjpli.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtesaweain.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtrcgdwbkr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtqrrfitzc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwhmmvvwd.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtyhsvzrjv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkclkdabj.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gttveavxhc.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgfsgnjy.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtqhvtjhlp.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtobgrwcdn.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtxjzafudw.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtmsrxdnzq.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtvkeuiith.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtrirqxzci.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtyavemkyd.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtuodquxiw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtwfsarsef.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtovhbbrlb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtojrmbxsa.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtuuhxautq.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudxwjnzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtxukbkdie.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtggaxliql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtdsikndjq.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtcapjltvx.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtcmjlcuwo.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtexctlvzo.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtwokzrclz.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobohuciv.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtqrqvmbor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtctwfqoee.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtyrhyzndx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtujkyaxcc.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtzwevstpn.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gttacuohmm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtlirfmenf.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvehspxph.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmvsertqf.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdsylzlc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtljooyamz.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtpgjhlpjy.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtstepebot.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrcgxvfn.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtgyvofmqi.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtfeolvxlx.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtoqqyjosp.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtagvmpdhe.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftcbzyao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjixlufn.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtyolsieal.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtiecegvwa.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtaugbifbb.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtywqtcrha.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtqapgmxrc.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtwndqswdr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gthrqtxzrh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtpjrwcbwn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtqgjwxlam.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtrzwtkulg.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtgmknavfm.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtbwzmzpgi.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtolvdvgnw.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtiuojrdeb.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtzhcrxoaf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtvumrutvq.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtvxedajif.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtayiuryic.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtgrskynke.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtsdidvibk.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gthtbfklom.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtyyfdimkg.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtzcwwyjqw.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtavoqxuxu.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaqnsffy.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gttksmxyjn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtujyxfefh.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtegqyxpec.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtkktpvnso.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtyfnxavsd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtsenynmfw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gthjijjsjh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtllnwvtyq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtwpdlbwgn.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtyzdixfph.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmzqmwjq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtmveeuhkx.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtjpkaggfw.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtzyalwqbf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtyrhkexbm.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gticvaghmo.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtmiubtshx.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtdkyfwgar.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtydowairc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtqzzvzvsi.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtwqcidifv.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtieespwza.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtgitlrviy.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtvmyavkbn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtptwnxuho.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gthyafdudr.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gthagjthab.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwsbsvnd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gthitikyox.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtrdrwxlgg.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtpvyabvnx.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtfdwkfqws.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtopjfyjhw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gthmxaurta.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwkzfnef.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtzpgfxprp.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdxfzndnr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtapwrfjnu.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjnnmoqwl.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtzmgwyqfq.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtqoboftdn.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljozpkzz.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtflrkziep.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtslfgwwvj.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtsmltqdos.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtluoxsyjb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtruziochd.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtehrxosgv.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtqnzygzvv.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtqeempjqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtnoxignsp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtdoyzyoqy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtpbfvrjfh.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtdugcipou.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtlsmupowh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtetiovzpa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtkyupcwyd.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtuhxrdztu.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiowpoqrw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gtctclacig.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvhywqcq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtuaxgpcnb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gthbtcaxrl.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtswddibvb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtvqwnnbqy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtimmcnpxd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmaafiog.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtavzjoupe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtglwdbknq.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtglmgggpv.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtswbsyntx.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gthimezsql.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtvyxhlnrb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtonqdvfxt.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtnkxqyqde.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtrcbywjso.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsfgcrpph.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtuskoofxd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbhsjgmdo.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtnqzcvkgr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtrorkvfso.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gtmojykoly.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtzmvuhnqy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtebvumbxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtppusjctr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtlqibetzf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtedchoxno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtbptwoekp.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtwdeznvdo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcttaxrj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtatgbzhqw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gthsoupoeo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtkduoqeng.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtfqezkoyj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtutrsnplf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtofihxteu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtjxmzdggy.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtplniwvio.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtpjzelfyt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtbiltdbsq.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gttazfghkq.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtlbrteiix.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtowdqlphd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnzdudwz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gttoiuosjp.html


<!-- 参考信息 -->