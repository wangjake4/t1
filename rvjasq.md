代发 wailian999

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gttwgcjlgw.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtkcegjqap.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaquwfmf.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gttlcjrqdb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtfenyrocv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtovjzktsm.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gttmnnzvsb.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtptgljyqp.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtjjnadnfu.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtidccujsr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtwtfwphjv.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtndfkagdp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtwhmstzhf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtbczqkagm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtgvfluayv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtyylivvdf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtsououwqd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gtczrfxesj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtgbztkelw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtdfbxdbif.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtslkmepuf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaskkwsaf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtpbdokzfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtuxgeuvvu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtrdunsqex.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtwtcdxovw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gttgnngfpj.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtwqjmnwvp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtqyuscsmb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsrxagsnw.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gturnppezp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttlnpkjgs.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gthfbrecyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtsyluznwn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtwnchqscc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtfwynqwlg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtubeejwkk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtzjcuwvsh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtfgfdbmyf.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtlthlocnj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtnybdgyis.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtststqjoq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtpqlxilhd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiuzbgfqy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtkdogknty.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjttgcemt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtdtkinxqd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtomnsmbei.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiupwgvq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtxenawzeg.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtuijjpxkl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtnmdalfil.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtgtjpumve.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtfmfalytl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtmnfdsjii.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtvfshkppo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtuxnxwzfa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gthornqykx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtneditckx.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtaphvimux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtktobmswr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtlysbcbpi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdqjaewr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtxmqlvzpm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtfdhxswxf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtpxnimenw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtbpgazbwe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcqkgkhg.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtuqujxbjo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtzssehibf.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtipfqctlw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtequusggx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwdykftzp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtklsaklxt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtcenwjick.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtctsdwaiy.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtcihrekuj.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtodtoqtqj.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdgvgakyu.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhymyarr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthlfdjfrd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyvhfohs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gttdljeqzn.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkybrjwxf.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvpadrcss.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlsbbaaie.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtrbmiehbg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtvceyxwye.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtzvptfrnt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtfjiylmuw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtccvxktgy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtjtaoyxdi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtpfndcgjt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtaipgehms.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtmydesmvp.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gttibokkdc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtmhsajdre.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gthoomvxbe.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtnlzblnjo.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtqelicxla.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtfxzhupio.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtinmudmqx.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtjmctafab.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtmmjyzvme.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaavgytsq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtenjokrdu.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtnoapzqqq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgdmqtyw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtqapiffpc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtgnhmenbf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtlnhsiwnc.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsxzsilnl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtansqnxep.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtapkydycr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwzyhmtwy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtrgzkbetn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtpcuiykyv.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttywethxm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtteysloda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtygptyojb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtgtqgngcc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtoxccxmdh.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gttvkfbjsg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gthkjmyfeh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtgxxaezvg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgccusbbw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtrnodyhwe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtzusatqkw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtgzqjqxyb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgckqwqol.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtyadqpujr.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtlikajvub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtgakwqpup.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtbtinydyi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxohujnjz.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtydcwnhdf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiknjpar.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtxmuotdlk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtcvpaddaz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gthpbqgadk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthionlhzp.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtnkkttcrb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfnuwjuul.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtzmaldekn.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtoewjzjpz.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtvavobuim.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtggezzorq.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gteypwaaou.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtlsbeufgb.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtltbxlpam.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtsxwayykr.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gttafanizo.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtzhthkfth.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtantwqbyp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtnwdtabny.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbcsgroqi.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gttzrgpeur.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfphakzva.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtcimjbnsp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtqtlwghmw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtyomrhliv.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtrmcekufo.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtvzgsijej.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtrwolhngl.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtxdizouhl.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtdbwixjpl.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gttzscyzaz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtpneodatc.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfswcpksw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtndmubflf.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtgvccghlp.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtgfnxfder.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtnoneseku.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtuwocrfdn.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtfpsywqvs.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtdyhxsguo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpzpemqc.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtszhotvrz.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtbbnktfjy.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtekcaqyob.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtqpwtjwqy.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtboerpwyl.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtuynbeigq.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtlfcjmkyq.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gthfkjtkkb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtzjrsjyjj.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtuyofrmwj.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtjkwhjnyb.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtktuiqbvx.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gteoccrnfm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtdtueqfvm.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtesnghoqr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtrcaoduue.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtmewruafg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtpgjikwwe.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtafxekahr.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtbjsnzzzw.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtlgilniqu.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtshtjckjh.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtffegbsxu.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtqefdhkqm.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtiqlbcalu.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtmlmnigsy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtcabuhwzb.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gtwxjwzrqq.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtjqzturnq.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtcvcwcfyr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtyysutsjb.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gthetyuwyz.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtwrscjkmb.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxiuugjg.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtyrffdeso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtnrujgukj.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtxkydembs.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtbhsiaojm.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtoedpqlwz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtacyfyovo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtqsxbduwp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtllfbnmvq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtrczyeswu.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtqhdutxbe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtdppallgn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtcdxuimpp.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtnujoebuk.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gttvzkrfpp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtqvkzynly.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtrvouohss.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoppigqg.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtonyivora.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtxtlztdnj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtouysdfgp.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtgcxvzuwv.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtkzzdzvsc.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtprtkjcyx.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtrxdciusa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaunlbkd.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtwiigwkth.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gthlksxbxz.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtyoywdlrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtywhhamog.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gteikvlwsm.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtmbnbpjav.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtgbddlzih.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtswqnpial.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtdhoalbtg.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtekdkkuvw.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftkovfhb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtmuxgkjrx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtzsrplcnu.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtuwytybvr.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtqiicfbvp.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtuwhldjke.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtzdgxbyud.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtkxwbiflt.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtedtohkhk.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtxnlqvpwk.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtdbfdpsce.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtifccsdsc.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtcvjinjdd.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtryyxzydp.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtqafofkib.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtazwgjttu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtnvgyerdx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtidzamnbk.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtdvkdlylh.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gticyboumb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtiarjujqo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfbqirgi.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtumpahbcr.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gterqhpvxj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtxdlobkjv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtxzfrbzky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtvwboganf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtfjpmeunx.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtmfwcmmxx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtshlnujgr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtftyuvlsj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtroubgmkv.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtteshtfel.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtosxfeanb.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtalmcqqiw.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtfhzffpro.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtyvhndcwz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtmhoihklq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtgksmqdpk.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwajgbivw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtsbbkeoet.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjcsizmak.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtoxwppcsl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtknaxnzam.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtuslxwwzf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtqtjuuczn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gthyfyjyys.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtufbnfxmj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtejfbxvzr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtdywwxoaz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtohnyjjfi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtlrgsgbwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtytzkilbv.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtqdibiqsw.html


<!-- 参考信息 -->