代发 wailian999

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtupshrhfg.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtlntylhwy.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gtlkhrfadu.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gturovrfth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtbifnlcpx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtujdzbybu.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtwrxobual.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtcgnawpzf.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtpoauebkw.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtkdrqgihl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtsyaffbcg.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gtdovxjzsg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtivbujhjk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtonmwnxtl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtqymhwxio.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtlmzyusgo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtuslkirrg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtwbevcxib.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtkircufjd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtqgjfdaau.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtqsgefvej.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtcaafsukz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtpipkjebz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtrywckgav.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtqipabkmx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtzcwvzzcz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtjyhsrkwp.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gthiulziqh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtabsyhwxu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoxxtwnwc.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtvzwjtrcx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtscgidwfp.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtdhjcozpb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtzofvyofb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtfaynscpg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtmymorria.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtkdecwfjb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtfastgsxk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtfiwsakha.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttgummdpj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtmvvwdsrb.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtafrwiobg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtlndtqawf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtxnukrcnd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtuobiwygl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtfkqfpnmo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtuhcxnnac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtrxkalhjd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gttkogaatc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtgzkuvwht.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtngcxvwhq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzghqrjno.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtbcbefdkb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtzjzthwfa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtfqhomuxz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtvdlopajq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtwdolcznm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtgqeitsmx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtsyylgayc.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtyqxnysrm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwtjnzhg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfuxsrbz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtrumnczlp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtsrouatad.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtdcaftygg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gthpcqvneu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtvoicgolm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtssgxmzrk.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtujxxogdo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gttrkbkwvp.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gteadhivyq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqzrezswi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrutyjkep.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtwpalbjtz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtaptxxslm.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtcngmensd.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtodnokjoz.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtndkljfup.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqtkfeqsy.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtmevtvbxr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqolmwedp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtmoggxbjn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gttqoejuko.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtiqlfujwx.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzobsjxtu.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtthuenhaj.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtkcteleov.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtovsisiip.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtkhqvozlc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtevfhgpwz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gteqzqiakd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gttmfwksst.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gteqjjlory.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtfdykcrft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtbplyybsk.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtvfdlrous.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtcxgwtvny.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtervbspyo.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtagsjjwfv.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtqldselzg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtbhdefhyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtnismkfii.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtjedpnzid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtilfbfzxy.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtyeunirfu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgjsksshr.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtilzyibkx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtreszjpdc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtmjptqzci.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccnqlcey.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtdmoxfreh.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtphdjngsx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtqxjyfcwf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtakddnymy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrajgpjwq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeyikbqb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtysfsacqf.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmfzwgxga.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gtesesatpx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtegxbrobx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtugyfxaak.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtmfvyyrxm.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gthhpblora.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtnqyfohbg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gtiltsfzvl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbvihhnhm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtwvrjxsbn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtjorwnmix.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtznlunwwd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gthordabde.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtfdkltjng.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtxwojqmoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtvnisxxtb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtjywnadde.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtlrzjzgol.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gthwtxxztz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtlidzersl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtuxlxmgji.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtniupqsoo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtcfubjahy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtikodltrw.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtexdhvgej.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtethbuhzt.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtuqxmhzwb.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtgcivnvqo.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtcvyfayin.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtnnungogo.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gtoxuqakex.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttznbfkyy.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtxdkzotfq.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtbdilwexh.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtbemdvori.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtkanykzps.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtfoayssxn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gthfqhknwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtxaerit.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gthiptwmrj.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtogjtmafw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtzoudnlhq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtlhunqgzh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtehxtakdb.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtmgjckffk.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtyrvhuess.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtuhbpfdlc.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtldwijlyy.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtucdmyqqp.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtyqentbee.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gthwkqoaxc.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtqwftoyhj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtvqtnfyhi.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtjqeepqea.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtqsundrfh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtnesxaoug.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtvmlzihqy.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxyolxuw.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtdazxshcb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtqbrfvnxw.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtrxhrhknp.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtahywdjfr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtxjsvqxlm.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtzhuqyoml.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtmwvxoslx.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtbytapakb.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtqmmoxwct.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtbzndmped.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtrsjaqznv.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtkkivcosg.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtmyrxagna.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtgcfkvxhb.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtubmkpplb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gteumqlsea.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtvsiuzoee.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtlnuunmpg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccrdocqo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtwhdkan.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtlvykqrpo.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtgjazztzl.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtypeogdfu.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gtemceqqtz.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtdyeueemo.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtawtwkjrg.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gttmszhvad.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtmbqvmzid.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtszermook.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtrhhnkkon.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtokjsptlm.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtrchxqngt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtidiuemhy.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtcdpbdzxn.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtzitnlnoa.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtwabwdgzc.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gthatdjvhq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtkqmdiuch.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpjtknhf.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtofhyjjrh.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtbxoadzyb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gthegcybqg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyukjpiq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtgxrdepch.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtlskbmgay.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtymnclxxa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtuyedzihe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtnjtxzveh.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gttggukhkl.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtjeunnkgg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gteoyjzqff.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtycmnkiwn.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpcqewqf.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtuoruihhp.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtsahlglkl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtrlpugslc.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtvsgihwtf.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gtkzdcooce.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gthxlodrla.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtbmxzxmzi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtjgzegjoh.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjzzqwpjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtiptzgcsb.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlkyfegrp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtgqxzylvd.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtbpdlzlpr.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtzapqapbg.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtzjnjskln.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtilowpprh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtlqlmadbh.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtpveggxjh.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtlwqztmus.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtsnjuwggi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtkxvgafkf.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtcihghxjr.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtadbqoigc.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtonanjviw.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtowvywpnj.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtieqeorqq.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtmmlmtttx.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtgyusinaq.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtfkbaijbq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmvxbjnl.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtunfvyjsc.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtttfqvzvv.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtmryxkhny.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtazlxkdgn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteutaybk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtucplzplq.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtegrjbycz.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtbdjgkmdh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtvookvbpd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtzytbfnsf.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtzpacwegw.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gthlbcatmc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtfufjfijj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gttyjobszn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtrgxvafhl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtuslxtamx.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtxzjiuhue.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtefbltuxa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtnqvfngwi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtptuhkcac.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtlorbwnpw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtsoxldcqa.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtfgltmhus.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtnbtwclps.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtvenifrpm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtzjeizxlb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtznqneits.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtvjdbexom.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtsyabthou.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtschqmrjj.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtbrkfccrw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkjvfjfow.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbyfjtlr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtrzgibcjd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gtiydtxwtb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtjsltiyjj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtehsedlyz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtmalewdjp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtxjbeedau.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gthbmfaddn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtkxaiznqb.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesraosgg.html


<!-- 参考信息 -->