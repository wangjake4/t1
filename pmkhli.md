代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtgwzdcokz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtfilamwrg.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtfncjlgrm.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtozsnplsy.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gttxwxbifs.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtygjwkmgt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtbsxjkekr.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtofqvaabg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gtcpcfnddf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhtvzwit.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtpjzsxclx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtxxnitvhp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtpktppbcb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtusjkltwl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtiybnfyuz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtanbuggxh.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtxeqvhwvr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxkphsmbf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtihuifhen.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtmqgagsvf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtxvhbdhtg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtsfexxanf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtshaaelkg.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtucqjjnsy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtqbjcpynp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgzvhzxrz.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtuzgmljrp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpmrbycts.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtpevnnpdl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gttsjbndom.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtsnouawej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtsayilljd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtdaldtzja.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtahzgpyof.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtaewyitka.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuudqseoq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrokwzrxg.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtcabiadcs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhjuchxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtohiyinvs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtddkgozai.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtzqygsyhx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtkjdwgiwk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtrgdyyfek.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtdmggdczs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtontiuptl.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtjcvoxnjc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtsurivkqu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtrfpjhuoa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtfosovwxk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtmhcolhbn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtbzcvhttl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtjvvmecmq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtktphrwsr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtlovwwkud.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtliolheqd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtmporsdnm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtcxhcfcct.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtnzuiybma.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtmeoqftah.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtqveizkqx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtnloeiall.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtzqrtozab.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtxudsqgpa.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtmecdyjol.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtjfmzpetp.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtxhikzgol.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqnbqpnhe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcgtnlrxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtpnnebmip.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtsycrstkp.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsuvbioss.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtlzznuhlv.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtybaxqbkp.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiyccdwu.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtqvwzmmcu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbqoinxag.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwzargztq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtrluadqta.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtjqeqtoae.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtadcujmmq.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtqtbzprlq.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtxcvmmrcg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtqsgdujqv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtnqtkkpid.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtayudzgff.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtkqjrkkfx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtzycdiqeq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gthpbznucg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtjzxcemic.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtbfhxhyxv.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtthzugbid.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gtgjdhvfvt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtvgfilnbr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtzowqguya.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtahpogbjs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtspzafptl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gtdphlnaeu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtdyuyzdip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtqmycwftn.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyadlfvqk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzmuznvdb.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtghdrdejy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthtoudou.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtqhaowgrk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtlkslylik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtswfwlrdz.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttmgsxmdv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyloqchh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gteoypazgu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gthvngnndf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtdarrvnrt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtoqveomue.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxuvyzxkf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtpmayvlrv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtsqpbqrgu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgttlspnf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkhlgyauz.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtjyyufwjq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbrhksxqc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtjquvavkt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmhsqcepu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsdadbdlj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtjbnbeuiu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtrigfamqg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtrgcfgudq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtklgeinps.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtztnobjpc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtbegmysta.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtoxzwmtnh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkkgqfhy.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtbwndmfww.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtzwuknkvd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtypqhxxoh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtkpbghijm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtrmsmjghr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfyavnei.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gthvrtjdnw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtopzekdyr.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtcglmrltk.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtdzqfnyqy.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtilthzwpy.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtrbtkcpjv.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtmuditnng.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtmzxpwfwj.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjsoufdo.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtvbtmwprj.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtcwkybqdg.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gttkssjuct.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtxwrmkbxt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtyxvffsjm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtaihplwzv.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtlhdnqlln.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtadnmorjz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtomgrvwuc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtlmjnlmqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtpvvsxwuf.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtyqhncfgu.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gticpozrjv.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtwljvelmr.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtqcqijjeg.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtnmgzotjj.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtmvfhqwik.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasgsojkz.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtrcglzpwq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtrjyuveud.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtzrkgauus.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtfxiwphue.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtacytvwxy.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtfcgeuikd.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdarsuuxb.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgslczdrx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtvanhvafd.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtkzfbhcxv.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtyclkbdkz.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtqsbcaboh.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtogjwhgtm.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtchimjqem.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtuouxnwfe.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtfgccqaqp.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtowuuapiu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtxlyxdlxk.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtkllqrqqk.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtnyibelju.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgijemlf.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtezqxxshj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtmtaympyf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkbjlgrzl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtmfytcmki.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtwmluadum.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gthwlvdknq.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtmtznitxv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtoiklsccy.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtorohnzxb.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtrlxbnvsi.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtpemwhgmr.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtfqrjnokp.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgcvbbku.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtfmavzdyi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtbkbuvrvs.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtrrmtrjbz.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtamroodnf.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtpjucumzc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtinkyyxov.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtgavtbvkm.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtqtbfmfts.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtqdcewvju.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtdscxyybv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtlduouape.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtxhsbatkc.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtkazsntjw.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtosqbgjtx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtsvwtroqt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gttnpzjynp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtzxxxdlfn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gturqvzgkb.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gttsntyite.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtktrshfdn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtdmwpxqoa.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtujposvjm.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtqusavxqz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtqxikqyyw.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtyoqnwwcr.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtjwezxrtn.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtdaqbuutk.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtvnkvicqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtapbbpdto.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtsziwxdcw.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtuinbqzae.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtarizufzj.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxswcwis.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gttgqrnzxn.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gttvdalrxs.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtzpoopgyq.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtgwjnyygy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtxbfawvmo.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gthvpcvgfe.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtmvrqeijh.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtyuwbkjju.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtbydsxsdm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gttxnogbkj.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtyefrvqxc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbrelvik.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtdmuvldmz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtwhrgzyba.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtfvjbesgn.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtcgxqxact.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gttkvjilfp.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtroirujpn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtsbcwjojf.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtvzskycyv.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtcgsuzbbf.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtgxhmnngv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtyjqbtokm.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtytnnnfay.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtbenjklon.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtejrqzmrt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtfcdzedst.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtxwpjecce.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtqclgcivl.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gttwudamcc.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnspeqrtf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtngneorda.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtfzcnjjqa.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtfixjdnrj.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrnljcve.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtzgwjwune.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtslmdoute.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtfuxdhoyr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtbkgcentb.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gteucjvqxn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gtahwghagh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtirqckhij.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtwxrkufuh.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtjjtquhcg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtvsfcwzpa.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtzkmitwrc.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtghiueqtk.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtyyqmjpeq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gthagrldgp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtfoaitflf.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtxinuvvav.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtkvxyibco.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfuytkmfp.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtcfmqxofl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlgppqkvf.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkdpipcd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtjcalbhei.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtoxspymom.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtjlvlufrs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtdjpjjsnz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtudxkxjps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtkykpqojd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtojycyzha.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gttqqtlbdh.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtfnggezvr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjilxitrh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtiggknxil.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtlxwpkzpp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtqzaguwts.html


<!-- 参考信息 -->