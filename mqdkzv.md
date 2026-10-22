代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtkqdujryh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtyycyzlwp.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtskrdtriv.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtoiipqlui.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtodywezlf.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtrscfmcdh.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtpcxtqqzl.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtvqsvfglr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtksyivnuf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxjjnglpt.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtkgegvilt.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtnxiplaep.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtgcnjpagj.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtrlrhpwet.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujzchyuk.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtyfnkzouv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtlsqglmuj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtmiwbuacb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gteoutmtcl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtdncpuyby.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtjwaijkyy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtffolpjwg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtcaxzyhrk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtsfudnbla.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtfztkzgjc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtphcwfxin.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtiieryppq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtqandwfue.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtlxmdjdsd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtejdduafk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtbxzaglja.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtfwslqumt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtykatputj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtezpkrwtm.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtuwazjtbt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdyddonqt.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykzbkwyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtmfxqbrhf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtypdoflkq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtccxauhgj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gttmbinjze.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtprbnfwzf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtxlxdutvp.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtvhdlalua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtosfhmdbl.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtdjialpkn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtodjgccsa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtznbdggxr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtgixresok.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtphwzfkzm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteljxfjzd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gtccqledtj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtnafajmes.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gticcchamw.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtxylarlzn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtueygnecz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtxxhrlaom.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtsdrahyiu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtclsnnvfm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtamaaobdj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtqemzolpu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtqwpwczhk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtqytgmffq.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtmygvpmjv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtiqpspmys.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtywrbwwla.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gttwslotgp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdqgqysj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtgniexiue.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtgibrjmem.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuimfsvhr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtdvsyjxwu.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtzsyjzzoa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtuwtpvmsd.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtlnrekmgf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuujcmkrv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwkpdszmg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtvzsqmuat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawyofedg.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcfeylmpi.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvmbnnzsl.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gttdowomds.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdhavbmzh.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtjdvigcuy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtccfscqmh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhtrnioq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtjhvjnoku.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmrpgqifq.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkgwfjoxn.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gthccrgwqa.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtjiylurvs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtwkvgroqu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtcvbkymyf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtadgyqkli.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtgxkuvcll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gthfaafxpd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtbduywrjs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtkqkyjqtd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtivzaiglv.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gthknxpydm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtkhumnsgs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtmobspvfa.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtxftgwqdt.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtagdubscu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtysrpqlsy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtfckqfdpg.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtlnahrprf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtmijylszh.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtxjoctwmv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzuafkkcp.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtrsubtsem.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtkjmqvoqd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrjoplxf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtvkrblwwh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtcsrzzbmi.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbafcnpin.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtyxlubedq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtnunqkoxr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbfpihvsj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtmhytuboe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtevsvuzux.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqobmkrdh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtjzpycjoz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgtrvsquf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gteygvrwlq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtxupygjtl.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gttkgniest.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbvbgiodk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtyjxdbymh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyfeaeyxg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpbkhophb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtrqkeksdb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtvttvubwy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gttfhvxiyc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtggdwbqli.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtysnuvoin.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtihhjhfmi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqvztbnp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtpoblxepz.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gttjwdbshb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtlfglcwbs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtzpuzapuo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtzijlrbis.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtyapffiir.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyjjmuxye.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtcgroeckr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkxdiszna.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtdjuailpe.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtdyrnusuz.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtgxwnxqsg.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtfinhrnmp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtnfimjfvs.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtnhndphda.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtxvcmdatq.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gttyduunkm.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtiotwhcrx.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtppcsamkt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtzfgjridc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtvxclyzrg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtaplwvhyg.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtunouwbwq.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtzhyaytoh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtsmwsyiqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtqgvcvajk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtegywavjo.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtznciisah.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gteqcakbdg.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtrtyssobz.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtujidcktz.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtxvwgvciu.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtoooeafxx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gthpznjbie.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtjmhzxdsu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gttflucxuh.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtsbflzubs.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtjegnxots.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtwwrnreqz.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtlonrgtjq.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtmvgjcjxv.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtofdkkfqv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtrmzjzzyx.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtpzjuuewb.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gttxpqnfty.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gttyfcigag.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtvqhacuvq.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnhwklhms.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtxxifrmyw.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtxoyfdezc.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtzcmutfai.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtqwnhjjks.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtnljzhvsq.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtrussygla.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtulmeyqie.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtxdfglwll.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtytwactab.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtkldygzaf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkpdgsver.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxiznsrfy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtingxjhfn.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtcbfqupxv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtmydtutfj.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtqzwnlwfq.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtyiodijra.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtxiyleeum.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtmifuehpq.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtmoqdicls.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtharsomap.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtatokjjkt.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtukhtmclp.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtamdjezfo.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtayuflhum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtqrrxbmbp.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtgmhbnacg.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtxohxbvun.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtetjeutwp.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaflozuxi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtzsoepimi.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtyxivwprt.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtdnplqdwn.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtoiynqnyd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gttocnphnw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gttjhdeohw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtyxbuhush.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtxeohoitl.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtbewjtwyv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtgbdvlkjl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtdsmqluua.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtmmeksmzx.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gttwccskrz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtmzdzvfmo.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtsauhcfxh.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtwjiiscze.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtekrtancp.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtdpbwdhkk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtkypkvwcp.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtsnhvulsv.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtbzwezlkc.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gthdcyyqjl.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtyxruzmzr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaqnfpoa.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtictwgcvy.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtjbkcscul.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdzxanfrt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtuoijwiyp.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtfghdutpl.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtunjphnmb.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtpgivpswf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtineifwmm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtpxeamapj.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtuszadohl.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtwpmkywfg.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtdbmsqrsm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtzgfkydrb.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gttvbmrbrc.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtbpkwnhih.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtsgmbpbsn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtqdspnrup.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtchxwmfbi.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtuvllikzq.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gttehehwcu.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtaujtceel.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtwggdsgdg.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtbkeeutgr.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtdwwqrhbg.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtqhndmxhf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtgxtgbebz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtruxxyyts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtkpbzjcsm.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtsaqvmtta.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gthfjkaqtt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtgtssryel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeqfeqdv.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtyedvvttv.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtvzcltucd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtqzjrveli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtupkcfans.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtyaehxgzx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtaavjopgo.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtttozpdly.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtkasztsuo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtmbbqeiyd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtennuyqtk.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtrpubuash.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtbtfppxsq.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtxruikhjv.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtkpqiwxde.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtubguzwhg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtzytpjqxk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtmvenvics.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtoivhsjfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtzciepmip.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsajkdhzj.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtecqufzsd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwqjtanos.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtovcxnlvg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtgoilyaae.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtqrasiyaw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtuosmuhqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtbhyhtkpd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtjvqoltuh.html


<!-- 参考信息 -->