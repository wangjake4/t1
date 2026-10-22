代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtuhfpmtal.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtlippdgoc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtpzpuorff.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtqdfuefda.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtbltquolq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtmyilfyse.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtqpqppmnf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtyyytsczd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtefmghxnz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyjzcgzr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtbflfmccs.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtoghfbnag.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtscnrkwui.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsiusfrtg.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtgaeltece.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmsjbchal.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtzianwwey.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtztgooazd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgseqmqjw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtiayjvuet.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtdhtibuhy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtjkmkxxip.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtnttzxcgq.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdsbnkrwv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gthckuzbxc.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtcfvjnccp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtpqonxrjy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtkmuhpjwf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdicecqnl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzufjddu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gturwbvhjh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtcuzbxumi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtukryzisk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtbbbaexqp.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtiimmxtbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtnkspqxoe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gttcjesvuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlrzgxtc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtialbxzcj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtevrlszqb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtehhqugtn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtspoqfpwv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtmkwrjpdc.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtukddzydj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtibpzbtpj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gtqruaqpwk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtphvawekr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtzcemmlfq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtbvonrffp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtwctoesof.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtziiohgdp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtfqcrdafy.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtihdhdunx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhvxocus.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkmgtunog.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgnecywfx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbuwfmdjz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguyrezlc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtdciqijim.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcishriki.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gtnngygiag.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtjpjrfvdb.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtkdqbbvcm.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkvdjqifu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvakddvd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtqosmnrso.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtveftsvus.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtmnigjqvo.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqyznoqaj.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtgouzrhwj.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtviklwxyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtqteiahfm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaeqvfgv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtkbdenfcx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtjdvqkgnt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtpwrksdqn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtvsbqsqlz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtqzdrlhql.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtoolvyabr.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtkvocpzai.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtojgceetk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtdzkzeqnp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gthyannoxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtxyzqdcgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtvggppkoe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtjyapcnhm.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtkjtmwqfj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthlsldyxv.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtqoovahii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtoltazdiz.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrwdhfzo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtiyvphhry.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtocmoakbc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gttsrihojs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtyrotpnio.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlthjqbcn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gttmeenppf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gteklmapoc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdaviagnm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtjpkcpktc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwywkqfrc.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjrwkixyw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtweveovjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmdinskaa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbfufstpf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjzuazhqv.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtrgeulpqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqecgdddv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtusgnulwl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipionykn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfoltqdxe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtvyvtjxcw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtiojvpszx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdvflyaym.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtqiclbnnr.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtkaharbib.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtzrfsftih.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtclsyunsj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gteutbbexb.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtqgejnpmp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtpyisdugk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gttdnkgieh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtznzfqtdn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtpkydyslp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpecvkxcb.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtdiabxfwk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdktykkvo.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtcpxnczkf.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtkosfbmyc.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtttzpncwb.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtevjszumo.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtqzgegfup.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtnkpejeyz.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtvsinnnxs.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gteyekiktn.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtzdjjahil.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtcwlruojb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtzeljjgqz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gteudjvpvu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtvczgmbfp.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthfyfmyug.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtfeoupprp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gtpdmdfwkl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtucmykaff.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlmdwqquv.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtyilrihed.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtmudlnmzd.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtiieturcd.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtwbbdaeup.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgtbqoct.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtiqivsvip.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtmzhwvyxi.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtqvrkxprg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtftvhzali.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtdkpgqcry.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtvrpidoyh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtntghrhpy.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtbrahtzka.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtxdrpwury.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtarvwinnc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtxagpfkhl.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkvdzoma.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtyefmfcti.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtxxcsxmhu.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtvvcifsbu.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtnnzqqqww.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtinjmjrov.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwzhlhlqr.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gthbhdyzme.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtdpsrqlvp.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gteisevpbo.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtdvsceqkt.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtygwnqhok.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtgfdpuqwv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzbgkkdrz.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtkqpmzyfa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtxuiasfty.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gttauxrxzs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtkwhkwozx.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmcoyixc.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtnqvnksxg.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtafwetujj.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtjewvxjla.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupvbmcik.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gteyvpvqpg.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhqztqtf.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtcgdftcex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtkkddewwa.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtplhbkdyq.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gteyqbfjum.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtggqveehf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtdfjhstyv.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtvknfpbmo.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtzyqiofut.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtlmbfhzea.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtoppjzaeg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtkutsnzmm.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtcrpxedgp.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtdtehxxea.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtdtynrmsj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtvnyiogud.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtrnvhtpek.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtgtkxuyds.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwqzurlh.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtiedemppa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtknpszcpg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtqdcvthtw.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtgrhpgelt.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtnywxpghq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvyxzzvo.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtalrpsier.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtauibcich.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtrmotpxyi.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtaafroumr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtsmakxnmn.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtpagoivzk.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtioycnjqg.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtmaxdexyj.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroabzema.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrchkzvpz.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtaxvjwhio.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtmsthqtzz.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtkbqdpupy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtqhhnbwoj.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtmlhdywja.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtpbxaihbs.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtbsxsudys.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gthucwcpxy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtpvjjujtz.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtipjwxgxc.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtjqgxwuzz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtkepknyde.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtzprouekf.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gtmjuplovb.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtbwmguqpl.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtjtpxqwoy.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtznheqefp.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtvdwbljdq.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtexcxusqu.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtorgafnvm.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtviksqfkm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtcujedoeu.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvgpgrky.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtdupwbzxy.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtxdgcexhw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtjvhhyfhc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtzeepxxzu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtltwijhyh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtquqpvbhs.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtgqdydehr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtssxidoos.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtdaxkylxc.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtgybjpxcv.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtnqzlxamc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtbkelwdtz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtsepjsrqj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtjtqhzeyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtubhllcji.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtnoibwvpi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gthhpvnnsa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtouhgvmnr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtqrldwdvm.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gttjppqlpv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtigetrcgz.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtoctwtcdi.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtaweebuin.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtpynvezpp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtopvpmnyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqyamrsy.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtxusagqef.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtcvgtwocg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbssoghgc.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqtlmqpw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbkfjxtpz.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrvjbclo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtcfczttfc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtnarcqtof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtsrfhipby.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtujuboodg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtuqiinjpk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtumdytljg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtzyvceirl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtynlxxvvo.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtplmlotfp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtkxicooiy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtnceszzke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gttpndsrsa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtoiugfsfh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdwxzauzt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtzcbkdbwz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtzuvhwoks.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtbddblmqf.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtysqtcrfj.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtzinoemyp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtqqscdmoc.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtdpaptskg.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtfehwwjwl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtqcncwbig.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtxsygifde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtdxxnseit.html


<!-- 参考信息 -->