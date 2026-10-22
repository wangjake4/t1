代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtmxokdpsy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtklrjtdxv.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtwccrfxhk.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtyjmhnbxx.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtwauzfaik.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtxylnclrd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtwbdrahbx.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtkqdnkeqj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtdpejbhvk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtqupluqmx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtdbdrtgkr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtkjvbbacx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtjfsybfcd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtcvvluhap.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtbjncobvr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtduwkjpsq.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtpkoydkoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtbktobdfe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtxqacfyor.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdqfepnh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiihtllgm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtxqesdcew.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcvuthnu.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtncdljaaa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtijtnhrvd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtaxntthtq.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gthqbvpwga.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtywxtngra.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtogzboaxj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtjdrwlsmv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgfnqdat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gttkgjoith.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtfhwmqnnt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtpjxicpjr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpjgzroy.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkqataak.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtozsjhmix.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtsjnozvjb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtguemvznw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtxbisnizp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfvyhqmbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtscdnfvhu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtdvvavxyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtcsithirv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gtjwaywmmc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsstwfyeu.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtyjwdjxer.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtoxdyopif.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtmlaylust.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtflosjhoc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtmtuttivw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtjydhqozg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gttinbyizt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtkdpwmrys.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtxuoomtsg.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtenqvruul.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtezrwoyjs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtqnguvbik.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtfdjorsxo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtsefpmbzr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjhtdfjl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtkjmddtlx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtvpfqamvz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtmmphynby.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gtscmkobop.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtggmmqjxw.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtufqyfhxt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtqxhrbeae.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlvpjchhm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtzmgcadln.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gtkgprwlfe.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlkmeaous.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtijqagbhr.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gthjtbzggc.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtozrsfbqf.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthngypvii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmkpeexis.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthxpnlxnn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtexznctfw.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtozbgvdub.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbewbdkvo.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtameetraj.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtrueposzx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtdosnomsk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtqdapccrn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtyupwqddq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtedxliecw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtlypgowjl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtyyojutyk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfrdwufm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtnubhochr.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtctapeuff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtjbduhvcz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtqlmmjwzt.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtxwoiliqr.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtovnmbukj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtffwvtqmf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gthcslgovz.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtttpuyqud.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtmakpuaca.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gtvfizjpre.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gttqempdmk.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtketswscz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtomsvomqw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtmwxpycrp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtegjtqoty.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gthutvmqqq.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtslalcqoz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtsydxkpfy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtxguhdwdb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwzqpjxtt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqiwcbcxo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtpyxdpnxx.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgozltmbm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtujfhprmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthqanbfqa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtlbenukdr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmsalzvwm.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gthkiczvqy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttdksfjat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtrjiksrnm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtdefbiysn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwigfduq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtxjmheghx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtftolypgq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqpcilldx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtttbewfra.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtsrnfcpan.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtnxpoqrtd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtrudmjqrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtzcomlrqq.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtlmpmnjgw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtkbloqjdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstwuzuio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtxhulougw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtjesbxuyu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtouoktkxn.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtbnxfpval.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxxnrrsza.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtswljleka.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtrbyszbfj.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtygopfbic.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjvbezviq.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtkvrmqtob.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtheatkrjl.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtfguwphnc.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtnnubwjom.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gttpocbyog.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtvlipovue.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtrihtclws.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtsjfronjf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtukxzjlxv.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gttsayefgl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtrdqswvse.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtqewwnvzp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtljoxfvco.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtowifpcqg.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsocfaiqz.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtvpcarwkt.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtnrebznew.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtoscxiyhz.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtaoseyfkf.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjufuhche.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtmoaqjswx.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtkxyivmva.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtyfnnitxn.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtpzlizxkg.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gttwlivgnz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdhejpxek.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtkuvgjjoh.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtdzuvokfs.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtheksebun.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gthzlhvvlr.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtormuskpp.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gteebkdvlr.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtwmygrbzz.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtasfmtnpt.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtethivvvd.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtqdpawpog.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtdpnjdgjb.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthovtmzib.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtiyihgebc.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtjwgmriyf.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtnmafokna.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtesxksoaa.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtjskiagjy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gteminvtgj.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtaksoxbjm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtyvzotnbn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtsgijysgn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtxnmlhoht.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtumvwnimo.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtzzpxntqj.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gthzmcfafe.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gttvuumciu.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtqfcelgek.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtpxsxngyh.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtslfozwzd.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtdajirjgj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtbcbugyeq.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gtcxpadnfn.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeeqwcta.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtddozzpmy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtmoouzmac.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gteejdypnb.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtcabvxcnt.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtibcvzdnt.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtrcxhivsa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwvhfsrn.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtqwgbvace.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtwuzgdhkc.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtmtkqgyue.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtcqscgywu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtxgrpwlbx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtkwmueura.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtenfwcfga.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtacetjrnf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtbudarxov.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtrkowraer.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtcoqmvnlj.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtspdmtouf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtpswcqyub.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtofrxhuzn.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtshnwxhbd.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gthfjrrmtu.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtkzztcptq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqseswqu.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtrpuaydjf.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtrttbwims.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtawftlmnw.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtcjmieulz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtjqilztgm.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtxomujupg.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gturjmxiul.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtzqdghccj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtzpftxvcl.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtjfzjmvug.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtigpycfwe.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtnpmxeosv.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gthigwzdfg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteigibwqm.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtchqyjpjs.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtzdgqtsgg.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtjrojvykd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtyzmdjdrf.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtkfeptpil.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtfrdwukjb.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtarfbqoey.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjmgpble.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtqohxanum.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtrwaqsqzx.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtcqdmdwus.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtxcxuilbr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtajzndtfk.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtkyelfrwk.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gttuwftdlz.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gttlalmirv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtfiuulyvx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtwldlgipv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtospzlvrh.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtoqhbkxtj.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthwbmtgwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtwuymtknv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtqnerlgya.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtqxxndren.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtsnmrualg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktmsgtnw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtfhwihnhm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtntfuiitx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwgprjne.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtxkenrpiv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtzddtoohs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtmgqgnhqv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtluhnfvzg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gttgrskhkc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtnhhckrit.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtqgsubvna.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtjvnsvnrf.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtyjjrqubk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtforqxspf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtiimkurwl.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtunqcgazv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtmhztxdcq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtddseejei.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtktwnripu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwzcuelit.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtzlurqpbg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtwoxnmalp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtivaammat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtpqmugsqq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtyiegdiop.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtprytrbin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtbrrmnhau.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtyywpytvt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtxpilmssw.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gthvctmtsn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtytfgfgfr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqyrvbqjk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgvpzffyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtbomeslzj.html


<!-- 参考信息 -->