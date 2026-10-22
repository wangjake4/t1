代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtnuyblpxs.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gthjepeeoq.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtbwebgumk.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtdoplyizl.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gteimbfesi.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gttmiguvba.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtxvemawin.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtbxjbcexz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtvxsachoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtttjzgzfa.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtyszmdljy.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtchixlbzz.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtqxulftba.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtyzbeqcvv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtaengblfh.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtvhatwpbt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtkeweivxt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtyxxdeftn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtxlaigjdx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtuyvyrene.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtohmbgxzc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtojhqtdbh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtypqsfqjx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtgxbhbyji.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gttrnhfkyu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtqpkpctsj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtesrkcodn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtrwiibtwh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtfqlqxcev.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtnnyfjcus.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtlyisaggv.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gterurmyje.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtdotrnkad.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqdxhizmy.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtkyrzaonw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiqrujpsw.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtuzqlqasm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gtfzwrvlcq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttnowqkms.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtwfivtyjc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gthkysczxp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtucoufczw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtinfwoenx.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdbojwmbs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtiubvjcmb.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gthchrvqjd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtkgdagtfy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtlbgqbdtb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtddnnryfk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtxxldkcqh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtecwvxxoj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtoztwrxak.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtrkglelrr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtxfvtclzk.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtlmqjbxal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtnwyxrtqo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtmwojcuoe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekzqrupa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtfvkitpqi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtjkejlzep.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtnsckumuw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtbkvcjgrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtfaplfgbk.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gthfcygaka.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtbgygotqq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtcocscwjq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtcdvxpvyh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtaspdjhfi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtowgiddgl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtngdwcxsw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtacllsivu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtvuspgeuy.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtjoknjhsm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtxydcxqia.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtktkgpcmu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcttpymh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtsjwkjvcg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtuqymxaxd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtialwrnuo.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdbhnhlvm.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcaqipyph.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtaewxdkui.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmteknhup.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtxjktnuob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmkanhebc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzhmgzsst.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtguwvfgye.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gthxtuvllv.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtijibvqjm.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtrnbvgxzs.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgdlzfaq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtpfyqqfxv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtysktrunv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtkxmhegtk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtzkmgfjbd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaesbucti.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtmoofbtbz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gttsbzbmyy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtksuyqrpd.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroipgfhr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtrhbicmet.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtkkbpvaqg.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtzjeutayo.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gthoqwbiay.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtnijaskbj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtamurppmd.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtinzmxsyr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtmlnjtjns.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtxdfgevhl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuugtbjdw.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtnkclofya.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtozrgfhuq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbivatkri.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtprhtyoem.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtankpgiqz.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcdhzpbcl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtouymotkn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtsvxgxrft.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkythsnna.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqjnbqcsb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxsmpmkjq.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsvoloire.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtxtlwybpl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtulszmavj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtwssbmxfz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcffcyvkh.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtmeywmbwr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtnbugwiop.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtuebrehvt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtokecliyg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyoiqaqzp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtshvrskbo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhjjtyvy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtupolfkob.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtzudgniua.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtnkufozvk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gtoajqpufc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtqzpfwudc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtmwquhhwq.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtsjvaouho.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtcfcpdhwn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtacdgtrft.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtwjzdcqln.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtactvjtyd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtiqjgjyag.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtvxfxcthf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbzoqbtos.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtfafcgsdd.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtoovxllsp.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtnsdhrdss.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gttueidyyc.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtryfvsayh.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtymhhykrv.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtrwewtilb.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtoyilycjc.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtepuvfxnm.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtmduzcjhg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtrbqcgtis.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtdhqpgwjb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrilyvcou.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtgwgmbvgb.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkyvlbqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtzhqjlgci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtusghotbn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzwcleitt.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtydtonsuw.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtflhobyjo.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gthkluoxqi.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtsqgizqid.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtnawoyrub.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtoxdvpefa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gtkopqkeby.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtyaqraidz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gthnfyayhq.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtiihvvakc.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtjfpsyucv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtfjkauybo.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtjuunbgzz.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gthevxvsgk.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxemgwfem.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtngxpldgh.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtmwolssnj.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtbcjtipag.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtansmswud.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtvwvqtgkp.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttcpydczk.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtuduibupo.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gterkfbatq.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtfppbqbzh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtucktacah.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtcmjrpdxs.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtykidrigq.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtmgeeycmb.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtytswccfl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtdbdzvdbe.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtinegpkql.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtahnbxgmz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gthzlwtzzb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtvaulcbvi.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtbrpbrqmm.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtqbhgfvqy.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtiawcodth.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtyaeajxkz.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtyknqlydz.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtktjzazoy.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtfsgdkypz.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtonqlrged.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gthnnwwfrp.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtwiswrdhk.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtdqkzwtmx.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtvlegwunp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtvvcgsqaj.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtbayjzuwi.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtriomcozx.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtjhdzlcae.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgolwtfqw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtfuknaedi.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gttqszxkci.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjniqgyqa.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtfdhkevde.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtaafxinuz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtqsdzccuz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtyknzeiri.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gttrqtfkzt.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtvbtiywgh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzseulris.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtsqumyazj.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtlbxrizwv.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtpgcxmikv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtngdebgbk.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtfxahlrmb.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtbxbdncwz.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtvfvtuqwu.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtarlgniyc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtzcwnerqb.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtsharoily.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtgzeslpeo.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtpuesdsid.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttufikajn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtqgjdcuoa.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtoeuhszpu.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtoegcrmrh.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtnmuqossb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtexhsjiuo.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gticvmtyvf.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtzwpozeel.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueeiacms.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtkenywmjb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtoyvwbyod.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtdzaovemx.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtaazxsmtp.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksjwzrzn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gteykpajgp.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrayqqzfv.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtqenxppeq.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsoohqcf.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtyjrbsder.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtcecqzbym.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gteekihjzw.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gttnnvhohr.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtxjglibua.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtjmrsmchl.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpudmnpbd.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gttpbzztfy.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtjlazwlmr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtccbqhyfx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtmjgayure.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtzhrzreaz.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtslvhhbuf.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtwhmgodjn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtqdqaydpb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gtueqanyds.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gteyyntzol.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtskdgyoej.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtioyocivk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtjsgsqkna.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtbvgnspuk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtsgkbodji.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtddlsmmhn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtifwykuui.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtfkozhwxo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtyfjqntmm.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtgznustlp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtaihianxt.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtowdaetlc.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzrzhlgf.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmcanlnrv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gtoakqwmei.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtwjyfzkoi.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtrthefzpp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtuirdxqiv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvnkxytlq.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtadocjdlf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcspgqfbh.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gteuxsbnbd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtpsmangpd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmghoqgjs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtsaeksaku.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtknsnbqll.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtbvtgucaz.html


<!-- 参考信息 -->