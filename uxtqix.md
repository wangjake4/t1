代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtdnhnlavz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtcdgtlwev.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtytsvssdp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtggvqjuor.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtukzxchce.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxubouboq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtlzqigemr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtuybkrdey.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtjhomajhg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtjzuxismy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtypclksal.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtiigtomvm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtdyvnxpyt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkropbbfh.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtlcuyggqf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvumdramd.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtstvkihoh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtwxqtixjs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtoaotuhmw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtpgptxkid.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtawncsqem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtofwznoci.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtpulifoiu.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnluvtqrq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttdcgekup.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gthgiafbbm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtggqiqehn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtcjogvqap.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtvzrqtydt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gthvawdgij.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtqptqrwvb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtbwaczjzq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtixlzjqpl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtmusopywh.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtankrtdpk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtwolikavq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtpavltwtd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtlbkbjfxt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gttcplvnax.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtrmvlhdnp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtmmhddlif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtqnlztszm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtgkjzxtxc.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gtmolqdgcs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gteaicolgt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtnwosbgma.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gthrbwpwib.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtvcxynrrz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtkyhdabsl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gthjbcuzhf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtpvbesgmu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtzjdomqzo.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtrrnmwbyk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtqojwefkm.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtyorzticu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdqyvouoa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttfbjdqja.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtduqktiie.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtstckesac.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuypbpuzq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtarmpvtyy.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtvzhsgrig.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtrybamyih.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtxbelghwy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtroqlvehk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtibnzhxiv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gthlxblkwd.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtocjiuacs.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnnzhfrz.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtcbqyzqyk.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtsczhuffj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtwprnxccy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtlggjmxae.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtmabruucx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtmfxvboev.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtvrbuaxju.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtzcmrwhas.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtqadzdace.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtkdekkurj.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtajfdztmq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtrzyshpqq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtmumopjae.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtqeffkunq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtopoecmbx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gthzuforie.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtyfnevfjb.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtixzewpqx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gttvbdanbl.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhkntvyp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyokaqwog.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpvwnoaud.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtjekgvzqd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtcroejnqm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtrhnzllfw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtbdmkzhya.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfsaaqnxr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtakgxpdqn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtbryxsmtp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtndjdxdbj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtohqjaxvx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gticpaavwm.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjjwmljty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtygtajygh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtoncydlru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdlyqsbi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthksfllno.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtrgqhbcbo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbjpcfouy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtwzariucd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtivdmjwze.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbcrroqat.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtyypwlqmi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtrtnvdgsl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gteuazxtuc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtvvmowqnm.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtkxxmcrmt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gttdppdhso.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtxbudzypq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gthxypawln.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtphctjiwm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtpddvrmuf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtukzsrdjz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtoqvcpjwr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtezkcitap.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsnpgpidj.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtupjvjwtr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtiftqrmmi.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtrsylckcp.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtlltrlwfq.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtygkostnm.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtzxhucdth.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtoxftptmh.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtwizfvbhl.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtdgzqytrv.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtywhyxgpu.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gthhfevmyf.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtnpbytgme.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtdanyzdsb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvhgnqrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtwerefixp.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtsmaonzqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtnpyljryd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtehocyfpi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtyddhnmja.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcrtbtto.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gttmfdsgck.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhsbsijc.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtbzzgdwls.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtufwwbyag.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtccsuslvn.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtszqugwqs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtndovafed.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtqmcqawis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtbwlbzxrd.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gthozmgeus.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtyxxpfxsn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtkedydptz.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtkoytqgvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtkopvwwjp.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtfqotbn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtkjomdkyk.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtlnzvechw.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtmvnrzcwc.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtvusykixq.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtloklekzz.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtrzqkznwg.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtpljljien.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtbsloyeno.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtnsqwdhrx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtcemxptwj.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtglovepzu.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkotxwyht.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtcgahfjwt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtqxkfunyx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtwpfvebks.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtcjvvbkfj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtjcggftxy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtcwejciqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtwwxrzite.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtecjhqvxw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnyxuxmr.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtxbjtbstv.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtujqtirxa.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtrxfecggx.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtmqiptzxp.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtjmwpvohs.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtpnbvpxjq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gtuhmcbkjf.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtvyrzcioq.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtifquvspc.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtstcvkdml.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gthkxpjskm.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtktqtkfdq.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gteaqdvbio.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprigjcjp.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtommuwrtl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtbfsxiqgj.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtjyjmusxv.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtnistkgkq.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtronevdfl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtljpgxrmj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtkkxrotxw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtdvosuggk.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtlozgbaky.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtjonnseyg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtztysrolp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtfemfdmyy.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqeuuftss.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtnuhhqdba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtxvdqlmcx.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzqiexyj.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtmtscldcj.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtsqxowjuh.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gttvmbleip.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtralltixb.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtjwchspcz.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gthybbsoxo.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtjiihdcao.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtejiijbjv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpuxphgta.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtvwxixqpj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdkhowzqw.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtgoxnkfqt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtacbwexmk.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gthbdpslfd.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtuglsuzdj.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtqwbnqigi.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtftiqwglk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtgdwwxhxg.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtviuxvcal.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtzgzidjpw.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtvkhrxeyy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtwhgsfffk.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtxsiizxju.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtfahhsgiw.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gttrvtwjpt.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexbnmyov.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtdybxjcne.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtraxzgncv.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtwnhsqbke.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtlyocvfrr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtxqtmjbez.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtzchydube.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtgdhfwytq.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtagzxbdbb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtdinqifau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtstxvjasf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtqydbicmu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtbctigwzo.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtzuysluvs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxaooyxm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtxiyiqgey.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtvoapcabd.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtmwnfolyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtydhuzgmy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtexixvoxw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtkhfzrdde.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtktvgdlxh.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtybrjwwly.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtbcvjhpdp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtepfcuqni.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtyalgrqhs.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtiqpzqdcj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gttvllirce.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtanrjrfgr.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtyewpsaju.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtbjbgnemq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtvoixrbpc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtxvayfcob.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtvxwuaani.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gttmpagojd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxjlmbiyr.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtdezsdxat.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxgkonqgu.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtjdipuyjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtjvujptjh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtzkbxjezu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtzlesxluz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzdrujqrl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwcrbqkw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gthpntnkjv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtcajlfkyh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gthuygxean.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtkkiltgzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gttwfqnxwo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtzojhzryn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtwhtnkuur.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtngczvgjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtldflmctm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtyhpgnwmn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtpdnbobrr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtzsanglia.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtifmnpkpv.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtudvyaczx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtfxuolndu.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtovkqgkhb.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtdxvzzojy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtckyormnk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtjgoonciw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtiybodscy.html


<!-- 参考信息 -->