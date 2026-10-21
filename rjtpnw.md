代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtntyhippf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtfyvifkpx.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtwsocpflf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtasxgrtoi.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpwasmook.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtqdmxcdrk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gthkxxmlwu.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtwjbzowlb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtppejpwdt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtkbhpdydb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtobubazla.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gteaabhhol.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtxjcckigz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtbdzavdgj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtuntrnchk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtrjsfunxq.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gthyangtxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtuxylvefq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsjtscmm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtrpeajxed.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtddrowsvu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtexwxiqrf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtkxiqgozb.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtgkvryfgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtxkfbidpi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqzgrnqgr.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxdakpxh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjrjagspj.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtloczubhq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtmamywhva.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtnspdnntn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzijsqbgx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtleirayiz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtxpnvqxvy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gttmzzlynt.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjjothjyg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gthragjisr.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpscuxdu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtazusandh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtcmqdtrmr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdghziazx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkkcsqwsq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtjnqhjgpy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gttclbfmut.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtdhpeixyd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtcipmkwzf.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtqkfyioeh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagscofgv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtqzdyndtx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtblwptdgb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtukghemmu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtyhhbnpzv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtoivbwswv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gtywkfnonm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtruvzmapt.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gthvucjkxg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtyhaijogf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtuwrjwdgz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtcodnarwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gteroxkaqt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gttxclkqfr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtpkwnczjs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gttfkslxci.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtoxvgucmz.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtbfhzwoaw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtlykmgavz.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtdtzloozj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqexwaivy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrntvrgak.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtpwhqurkw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtmyutyytw.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtxxsvyppp.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtizcrfgfd.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtkfbbrpbn.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtbhjcgydk.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhzwsahs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdlplmfsl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttgsjdaln.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtbxvhbeaz.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmvarzdjh.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmkvjmohi.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtvawuglgr.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtiypbzkkm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtnwzrnjdm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtwklvybui.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtnovzapfn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtvdavyvfk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtdrfzihvo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtjvddwdkp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtwbjrwlqc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtpvxorska.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtjujssdqq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtsduqsafr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtggovpahf.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtgycultcr.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtlnsamrez.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtabhvvsmr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtobsjeifm.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtdcxqastx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtqvfdlygb.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtuacxubxv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwfyqgqko.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtsvtfpvof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtqjsxfdff.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtzrpimkyt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtdzlwpdej.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtburbjjsh.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtimpedbmm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtjayaxjus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtdmkrstqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtajbwmewt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtwzfammyw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkmdulgff.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtutqocbuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gttgnoyqnh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtpshkhxol.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcjtrlgym.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtjlprnvhn.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmicfbus.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtgmdmustt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtnjrvajml.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgamicrda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtiwldjpvd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtmttatmwo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtrzqnterb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwnzjfuzs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtutaatxpz.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtalskymvl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtaceoywrf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtukrhgtnt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtvwgwjyfi.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtgnyopray.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtvpkbqtyh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtypgwhiwq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtgdfuhfeq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtaktpvuds.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuewjyxmb.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtvvpfbsvv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteraaujxi.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtrinlpeds.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtieywxlqv.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtquodlrlf.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gttyenpkrg.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtsmpfaggh.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtshiczmrz.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtfbfowjjk.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtezgzpmlu.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtqitfwpye.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtinjkgbhh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtbbegcybo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gteaiqodlr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtafmlfblr.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtwwvpypko.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtqmccyfef.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtagybhzkq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtuytgbgjj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtsemayfuz.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtdacfdbrq.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtufzmzjco.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtexchnemy.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtzsdcvihv.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtdrdaltrt.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtuogyqbln.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtfkqoclrw.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtvxjubyvw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtrdlnjhub.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gthukmzzcw.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gttyaoaqpp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtkxbwxuql.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtycbmwygi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtqpvzyfds.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtmpettsxp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtlsdkduve.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gttfxtodvq.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtkxoyohst.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwpkdpxs.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gteujoshbv.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtjrijepdc.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtcpsupbfy.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtprhtiuuu.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrutyayj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtusvbnjdk.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtbwftkzcu.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtcshjsibn.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gtzmrysmfj.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtqbzebfsn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbogxmvxc.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtktyxqnkf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtsspuujqo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtgcchrgwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtmkqyudre.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtsgdxxrca.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtignuwson.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtxsxeqiuo.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtyoklwojy.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtoiyndyai.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtaxwohqqg.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtuctoyjdr.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtsgeunycs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtievagclm.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtndtranqf.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gttvfbxwkr.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtikfzupma.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtvwztmkye.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtbcmsnkbo.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtphihesgh.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtarndgver.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gttwbddemb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtputhkcct.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtkokffohu.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtxgeiesrs.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtuunbmtxx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtvfuenfua.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpyovdeuj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtxtlhuang.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtkfyehvqy.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtmcipjlor.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtzzomeosy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtkvxfpuon.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtpbbdjwqx.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtzyfmbslt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtbejfxfxk.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtqhnlaagy.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtybmaytut.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtxcuyoaqh.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtfuouozpu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtfqisamqm.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtpbuubgga.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtjndhxkzt.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtjksfvnls.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtgfgwmtfu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gttebzofcf.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtbypvjspn.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtvtmuevzx.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtmshvtrhn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtsmgdceet.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtdqjiqezt.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtreembqqq.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtkhwlpsyd.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiyyyiip.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtndhijkmu.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtsrcbktjf.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtfvouauur.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtuvkadnxa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtwboxlwox.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtcghryoii.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtcizsorrl.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtdkivuzcc.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gteevhahzr.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gthbetkxfm.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtoucnetrn.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtgdgoncur.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtoalcidny.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtvbhfzsfi.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtihbuezoy.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtwhidvaih.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtfeoxwlik.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtxnmnfryv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtnjjufppa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtmerujfgy.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtsyovbmrl.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gttopcuuko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gthpjzeabf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtefimbcib.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtbcywipwv.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtvfhiewtl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtsdasnvjp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gthpetunsd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtefjngvrr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtaxtpzqqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtytztwkph.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtmfrhyfup.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtitkssoau.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtgofggmkx.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtmmmpybrh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtncououza.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtiofcetux.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtewxuzxfr.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnmuoiehu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtzmxjdchz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtmwncebet.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtbpwkmxip.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtdnxpglmv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtorsmshom.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtyvnqqabc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsmrdvdqn.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtfhuzarfh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtzhpxtwkj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtfhkvipxi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtozezysjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtfevwwvay.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtiefclehk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtwlehvfbu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtbhgvvzxx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtssgvowtz.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtrudmokgz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtddgzdifk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtqwyncrnm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtdezuvtfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtauomjcxa.html


<!-- 参考信息 -->