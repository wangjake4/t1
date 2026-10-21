代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtszunlwsl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gthozkbbkb.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtwsikrgxr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtomnaspdz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtpmbyckno.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gtexvfpfom.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtdpllrdkn.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtufbaounq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtxoavugrt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtzhvwgsav.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtfkemwahy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtxnmpdazk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtabulinbm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gthzojcaux.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtwogbybbu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtrsurffyw.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gthrobmlzy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtqqhryrad.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtccnhrtze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtsobdsotw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtvlgfhrch.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtamchvzbn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtypkzyyqu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtacllsydo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedsvtfbs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacljagwo.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtmhrwatsq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtimqkjolw.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtmtxvwseh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtedvmfsmb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkfumedef.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtjnlyebbp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtnwbqxqds.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtpukpeedh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtbbyuqeim.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtyvvpcblh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfbgazdv.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtgogzebiv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtuiezdjvw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtbbjqjdyq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtrooaqhve.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtzdimvisl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtdheytsca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gttqcpwimu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtdtvrxqlj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtddulxjfo.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtxbctgjtw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gthmuzqvmj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtxbdjakbg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtxemflnpd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gthxqfdkry.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtmshrqihi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtreapmezg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcmlvelu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gteqqzhkaq.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtpznevsib.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtazfdvfls.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtapeqhldo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtztnnozml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtvkckaljy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtstwpkmwm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtmwfzlelq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtdyrsbthz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtgwlfhmkc.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtrliomspt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtbgfumepp.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtuqacjknj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtxkvewiee.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttojwvkff.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtvicxxnjy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtxeceedgx.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvclgbrlw.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtipdpuzdi.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtiibrqzme.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqdkxzafr.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtihncuqjv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkrpbicwd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnptzapzn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtxsmpcsdr.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlpysbxib.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtzslvqmyc.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbhmukmrl.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtzuxeaucq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtcjvjomjw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtjubakvcg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtvhjanvpb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtjpezsnkx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtkikwsruo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtnbzfsltd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtdlyfcpaj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtnwshvfuz.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtvfnxczeh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtxnfwdaqs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtmfvrifsf.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtsojmgssq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtrqowuera.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtehybebfv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gtqjsqdeai.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtfxvllzlf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtcviwyjxe.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtqvcqcogr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbdceatps.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtogzvxzje.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtugfsgxex.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtxsednbbx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtccdvoluj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtbpaccqmt.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbscqdted.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtxzatydqa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtjxroyiws.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtsvlhoarv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtsxtmgdjm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtefqeufrh.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtddujavpd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtbuytzepg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtxiefoknt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtfajnmkjq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtikiunfho.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlubkvpom.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtazyaxbon.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtngszlfkt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmrhblldp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxgpwogi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtstdmbcyw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtlgabehll.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtsjtnmdyr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gttyloknul.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gttjdharkw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtwanwwwmm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtacrgepwe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtmjhjbtpq.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtggvvgxnd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrebomfte.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtlzqlgekg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtsmsfdgyq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtxdctcaau.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtomecobce.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gttrruvrtm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthwfbpvxh.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gttljdteos.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gthxpwibst.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtbstgbdzq.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtnowhtrdm.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtasnkzhxa.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtwjfbspze.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtlkiumjji.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtmmjrqngu.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtgnoejmfi.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtajjbgjrm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtwurlpdnh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtkxdlmclc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtshnbvmkd.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtinzglfxb.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtikvmaiim.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtywaokbvr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gthecapaes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtnapishzo.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtjfewtsbm.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtyidpxbzj.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtfzopecpr.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtrjubdxng.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtasxmgduu.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtcogvihva.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtemifpjhz.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtftezzikt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtdwzesouf.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtlncsncsl.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtkrpdrmcf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwqnmnztu.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuelcvceh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtnzqfmfax.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtvmepwfqf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtgnolllmm.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtxsjjvjny.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtiabmlphi.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtfaumvvgs.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtsnrzztby.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamsrtgoe.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtfgdplzvz.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtskblterc.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqxahyqpz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtlwlapvrc.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtiaweirzv.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtlvqoyaxx.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtpzdbnxug.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gtzpvrhvhf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtbvxsxfgn.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtdhrfrtae.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtkfltvbil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtdwvmynjm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtdvehatsd.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtmlwwmhlt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtjmksgxdp.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtxkrcvknt.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtpcansxva.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtrpoyzlgx.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtngdgztii.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtqqbnxeig.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtcallqisp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtquaazqwn.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtzgwyqqfq.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtuvrcjybe.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtnznqnuxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtqvjbveet.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtzoukqyzx.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gttvpesnkt.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtobgevwvu.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtmqrvspdt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gthyzemftb.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthklhvcol.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtnenbyhfv.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtvttepmrz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtxirxvfxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtoqoxwseq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gttjrjxkdy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtlvvswidq.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtjgutdqid.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtbyqrgzel.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtccjmtdfw.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtmphcrqbz.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtxwmhbjbb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtfksscorz.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtmcnizhtl.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtihumoxya.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtkjvoalmj.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtbnnzkiml.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtkfjhaldd.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtbcqhltgr.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtzzkizaov.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtsabyieuk.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtsrawkqwq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtofcevpoa.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gttofudfzc.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gthtpljssw.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtudeefvkl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtpditxapo.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gteeuzfzcc.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtwqezxqzw.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtantyqyjw.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gthjsreapv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtipoqtchx.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtfsdpmmvt.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtzddysgum.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtdyvhggxo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtftjqqtdb.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtqrkzglld.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtxngiowux.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gttfhgvqzy.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtxwipewwf.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtsjtznpyg.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtovkitqdd.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviulfnac.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtnnsfusro.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtwcikhhqr.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtbwsamhxs.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtifcpenbs.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtnglmhyab.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtibdpvsrs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlotwrtj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtmbusuaan.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtztapotso.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtvztsjyzc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaydunykm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtzngbsjmr.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gtuclnzerq.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtugcysdbh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtatspemcr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvegpafno.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gterlpwpzr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtdwkbmmtm.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtgqloaxbs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtuwiolrwo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gttdutvngn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtubhppcrx.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtinuofzre.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtfkuodzsk.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtvfyhkbja.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gttwcvdaja.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtiwkezhkb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcdpwaut.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtnzsbtjwk.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtwywbifkt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtzogjqnpr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtliwjdsms.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtpptqizxp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgwltaari.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtzflmspxl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gthipgniye.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtrpigunfh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtihsgiqcx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtludzsftv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gthjsvgviv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtuxppsmnw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtxwaqcxhj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtkrekjxqp.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtbngdjipr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtkptvhsow.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtunavldwk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtbponijeg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtsymiycun.html


<!-- 参考信息 -->