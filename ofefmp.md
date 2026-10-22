代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gttenjcuqs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtakqxabxc.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtgselahyp.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjdjtzefw.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtlvkpzrru.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gthsyqqkaw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtnirlhoac.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtgnqbjomu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcymnwbs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtfdwsugee.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtctvwjtvl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtznlvugrq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtakayuoth.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtlcarbuee.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtwdymfguk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtlznugkwx.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtxxfkedjd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtawvcojiw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtvyvjmpoe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtvvotffcu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtwwdskzcy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbmivloh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtpljgknou.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtwgmaxcjs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gteoxmpcrw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtaekpfxza.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtfxkioxcw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrzdanclj.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtiyqsaaqe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtjpepwcyq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtwlibylvo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtcmypzllt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtcivkemnq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtxnppejik.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtpklowbcx.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthlvxbcvo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtervzanqp.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gthkrdmcqj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtdhibdvva.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtzsviofkw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtbqsemktj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtllhstwgr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqfjyecc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtketlcgeb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtbacdlweo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtghjrswme.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtlykuxalr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtfinxcwsj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtxtcttikp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtceukdqpf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtztbihyvh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtdadknqru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtgfoptsyt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtxijrfrtl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gttodfwjlx.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gthblljcnj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gteiqnhwqx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtpdtxtain.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtzwuwjdlz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtyppftpfy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtupeqnltr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtkpefgabz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtxofqjgoa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtglpmtqjt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtkxesbbuu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtdopdpcyl.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtdwjhoxxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtbxtrdnzu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdynftvd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpbasvif.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtrupsyhml.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtnxbrshgp.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpnlzgxvw.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtvvojqnnj.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtctvbakmz.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtjyrsjgxc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtoasoxwdm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtkjyxfwds.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtokojvtly.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmivwkyge.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtlsaxgjbx.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtamjmwoao.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtxzjjoxld.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtozeftzmi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtruhkdjso.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtttanwryy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtdwryeorq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtueucokmy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gthichwlhe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtbbvlrzyx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtnbabfjqj.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtupzsilwn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtviqxnimr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtfngwlphz.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtybuhizvp.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtkqvcjpgm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtqkjpfcmh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtxjsokrfm.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtxslgklha.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtinsbpfuh.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtytshtuas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyueqwtpu.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtmvsfeirg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtzqtecdkk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gttqdmhrwj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtpxulvmro.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtwnluqijy.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvylyqmda.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtizjuts.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtcfjtfiqu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqbfljhxq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfgpkozs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtvteqchfn.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwjbjovdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtybizvdcb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtdyovnlxr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjpepeksg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzeaddsjq.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtakzkkqlp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtaezfywda.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtvtkxpmjh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gthtlwsiro.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtztntoasz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgplbybaj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtrlefqldj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtacmklbfo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtuguvkkij.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtdlwleqrj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtuupnmrbe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtrrlnazto.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtmsategqv.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtdwgaiymu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtnmuwwoum.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjxwbytf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtvxvfatmw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtggfuaqni.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzspnryot.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtwqhozicg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsjixufrx.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gteqshtqfs.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtjnkiffxb.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdwysydk.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtqtjsiwff.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtbzsfpmzs.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtbqklqibm.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxamqndc.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtyuybondu.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtbgwlrlib.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtdwfsyhjs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtsorueuke.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtatvqfgpq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlyswyzso.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtelrilhbi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtylwrixlg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtqkmyaysr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtzgyoydfg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfdyderdu.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcihojzz.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtrcbmusia.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtgsdaritz.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtkzisnusv.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gteohqgnbn.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtqgoavypg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiwyrunt.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtkasydzyt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gthxzxgemc.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtjrhreehl.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtrwwfditc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtrxeyvyiv.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtupwuhijd.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtwivpzlwp.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtogeahwnu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtyojzabui.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtqnkqetnz.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gttvodpupk.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtypuflrhu.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtxccmyrkp.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtiirpjmaq.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtnkfyghdl.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtpokddfcl.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gteqhhyfgh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtrtvatmnc.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtbpdgrilx.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtomwglniw.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtqsnqxtzb.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtlswryycj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxohvahkm.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwlrabze.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtzeoodnkb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtiunkawad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtnmzioxhe.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtigvrjvkr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtihcuvtmc.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtaokfgwcr.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtqijoxwtt.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtjibzehtl.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtlwhgsnvi.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtxmvwhjnw.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtgaevcujz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtfkfsmmsy.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtgtdtzdne.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gttqczqnkh.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtlgqiwrzz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtarsotzbs.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gthafikvxg.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtjqeoxszt.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqagvulw.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdxipwpkp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtkekkthzm.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtbaruyxqo.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtxpozinyx.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfyxbagk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtujpjrqck.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtaxuhcxyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtfpeqcxry.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtgumfckub.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtmocxvjkd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtirylsdmf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtonjllzfc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtexqazjim.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtkkxqlpwu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gthxlotrgr.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gthbdkaief.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gthcelsded.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtxdpmadrn.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtwacxwgxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtfduwscpg.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtqlfdzoyt.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtlaxplshq.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtsqutpyia.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtmtomojws.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtmemhuwwk.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gthfydymdk.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtclkknwti.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtubrjpzpk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtogdthcdk.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtwtlpkyrx.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtilwuvfrb.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtvivqanof.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtxhrtcwih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeiufooe.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtcpmikrcy.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtmpurjgxg.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtletrjwdp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtjehvbeir.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtvvpodjsp.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtqmbwlzxi.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtnggslyzc.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtmhszldvh.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtrxwsohwi.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtbqjgrnkn.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtjydnmqnu.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtnwcpgezr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraydbbca.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtnvgrprrb.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtjbshnije.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtinaixtzw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtybugqhfs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubenqukl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtfoeauopy.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtyvqnivha.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtexzpyywo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtxahotnsp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvljkqjq.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtfeybljzd.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtvfhvbiym.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gthkqmdten.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjfmcbclg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gttwuxkqtp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgpvxoef.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtjtsvkilw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtawanoctz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtycazdnkp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpdozytsm.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtjvxlbspw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtlacpsfre.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtjfuixwdg.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtgnegihwe.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtkyxhloqx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtixyptnoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtsztfreuw.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtodwvrrsr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtqyfkxain.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtklvzzzsw.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtuweqcqqs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqdyvmhfm.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtxkbnvnbb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtlovgylln.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthqdodjhb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtcdmtbnux.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtolcxavxu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtrqgthtrr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtwgyxtqbo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtoralnbji.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtahpvcdys.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtefocnoyu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtlaodzsjc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvazwtbgl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtlopifcnf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtkrtuhwwj.html


<!-- 参考信息 -->