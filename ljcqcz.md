代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gttoztkkih.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtorjipszf.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtlrldmezh.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtzfskadbt.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbsfokeer.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtlbyawusb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gthjqjpufz.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtgyaazsrj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtpurgymly.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtsbgbgzeg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtpcylecgt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtrykstcdw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbchlktis.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtwbnziosd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtkdnliwlm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtnjigurte.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtpeqsuaqw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtdufwgbzq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtbooxbvjx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtvstaetxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtpjnwjvja.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtatacertn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtygxowogy.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtxrnvvkhy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtfklzqski.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtljigelas.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtoiupkkai.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzrmyvnyr.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtzsfpdvha.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtwxfhhpdu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gthtnuqfjs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtlfnkmwuf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtukqfpmhu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gttdapgnkg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtepkkofve.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtvlxefcsq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtmmfcjpii.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gttrnxggwl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtapqdmldu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtocmqtgcm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtzjdgeksi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtijgchktl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtmyzstoql.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gtzorpxduc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtwppugzfa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtmmbkpede.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtckkzwfpu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvivsbad.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlgdilky.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtzlamhnya.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtpwfrhlmu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gtglyuucqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtyrwplirb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtedkgjern.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtknfvztsf.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtdmripjza.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtficzclfd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gthguohfjj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gttrgchcjb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtivncxlnw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gterzwpqrt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtlvzfnxoz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtshpclxkb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtnyomeqao.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtenmrvash.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtbflryszn.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtbypybqun.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttsvvtkiw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdppkzfue.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtkprbbwtn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtswtkbxvl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqqpelbeq.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpmworhhd.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtvlcevqzr.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlcythxcp.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtycfeefvk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtatvilglu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuernuolk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtuvaneoie.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkhtdwijx.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkysnuysj.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtexnmcauq.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtqdzjyimv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtpekqgrkn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gttxywiyrs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtjpegrolw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtgcvvakeo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtbksszljh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhjprfxq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtrpojgmdh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtkuhqmevv.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtpevqfoze.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtlnizsmho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtuqxqqewy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtjfbtzcgf.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtqxflaqbj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtkkujsjlm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtptwonpiy.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtvhtwindd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtphzfgeyf.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtjgzpxhjx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtpjmfcnwl.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqucuquxd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtfciswhsl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtjwxxmlsh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtdnnrmzip.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtoydpmekm.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttelzxmss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkilfzouh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gthoiyjcgf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtluhdrfgr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gttrkljqxa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbogznfuq.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqvwgycdv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtydlwaxva.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtruumgyid.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeqqoooi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlawfnhqy.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtiqiuebgq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxalmdctf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtnwlelkhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbyuwqgio.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtwqygipvr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtcnrvoozn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtctscycdw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtpwfnegix.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzehqckko.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtxdeggdml.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtycridcjt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gttsurdtcf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtuyeuhuqi.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtrxrenqzi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gttzeanvlw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtedflaxdt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtutfikzmt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtepcdodgp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtscarnkrt.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtxxtwtnwq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtslcidwbl.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtmjmxccru.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtyzpkvais.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtuylqptfr.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtginmhppy.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvckvjdea.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkgbhxcdr.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywvtcvct.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtavxshajg.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gthsxlzigq.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtcvqsauan.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtkodptfoa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtmqsfmoir.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtkdyfaffq.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjepttwcb.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtchpaywry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtfzzfvhin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtkzkcjxjo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtfvghbhbw.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtfdnnothj.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtsxwavwch.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtukhwetma.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtbjtbdcew.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthloxwurz.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtnpajiwqu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gthocftpux.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtxkqvdiem.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtozdpvqzl.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtthnfdjwg.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtaotbvcbp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtjltlabnc.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfrmgzrly.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gthvuqjvvn.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtldwrxyvn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtyytjybpc.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gthgqxlivp.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnuegbrw.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtgbtklufv.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtelatdpfa.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlohuizkz.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtfaxaiwnt.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtsrkfwiyh.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtotquifhm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtcegpzzcp.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtdyjavkwm.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtwtpgcswi.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtrltxpoqs.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtovjsuvui.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtdntlxoib.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtgylxqxbt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoggarqaa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtesaqvfbt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtgxhvmmbf.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtodubvtvr.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gttegsiknm.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtcdciawij.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gthtbxfadx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtahtajrlk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtwuivgjmr.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtscbnlvfr.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtqotooxem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtcgyfkaut.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtgyxoyoki.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtjjdmjptq.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtgcitfqyc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gthzgaeleh.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtqinifudc.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtpsfcnuyp.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtalgffucs.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtavfmganb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtpnphustr.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtfdvhjsql.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtfupeizzw.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtdfbbrpfh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtxrepyyug.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtxbcdljyq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gteqggcflq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtblarmokn.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtyolcvlog.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtoswntswg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtkcdfaers.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpmrerxrl.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtgqflslnr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtvjhysplh.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtpwampouw.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gticfsdfqt.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtpmvqnuyr.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtfaqmyskq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtbawvohwo.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gthoqipddk.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtehzggowb.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtclkdzdyy.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtbuoykjqp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxesycaxe.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtcbkzfads.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gthauszgjt.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtbdwdtcao.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtfacllixa.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtqjvaaskr.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtlrirmztd.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtabpxwldo.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtkxbfgcow.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtlbcitlkg.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcljnkcgw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtatfhnnav.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmmxmactp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtdxqemwlr.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtnqbdelay.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtnnokjlyl.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtjmzqfvzu.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtqpfqodwe.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtgwhscpud.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtdbchepgz.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtpuooyiff.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtkbsxzcyb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtbkhvbxui.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gttcjxftgo.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gttfwerkfq.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtpzpiezyk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtwcqieryf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrrrbbxf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gttsiziuxr.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtddwmkgrg.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtteagxhzg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gthaocnjxi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtphjyczvw.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtapdazfxv.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtjcgfooke.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtfrbgptcg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtjsemuzce.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtnyqpvyku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtkfzbkrao.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtrbpogfmk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtteddnqxr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtvkpilugw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtybpisduu.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtcakmkauk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtynualcgj.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtqjmnqarq.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtbaweogpi.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtzrmujpqc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtmwzsetuc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtkoyztvas.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtgbyyyykg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtpowumlxy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtiwkwxecl.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtawlsnpqr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbhueglz.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtqxzehugm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtppjcpkey.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtfbbvijrq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtjdfrhjpd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtdggntewq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtnhrjygza.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtxjgpxumh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtfgtzrsfb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gthkznzith.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtnfomhlsg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepvijnlt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtsdirwqwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtlfwmwvve.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtxwmvdhil.html


<!-- 参考信息 -->