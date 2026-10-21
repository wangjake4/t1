代发 wailian999

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtwaimfxvq.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtllwxvhqy.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gteigcxzir.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtkuxrbnto.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtuolfilic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnzsmoxnh.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtpcshsbxv.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtzngsgard.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtrwksjnph.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtxdpyuwvx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtcbdltcew.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvqbupuz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtwhsbytal.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtlsygrcqs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtidpmeano.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtatgrpyfb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtqcomrsjq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtirsidefw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gttykzqhpj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gteejxkdys.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtwznrywju.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtenstcyyf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtxisqnxyw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtybcawupi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtthcpuegs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtbfddejlt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gterjjjucd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtyepefqdb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtanazmuok.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthljnzzwb.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gttrtmykzb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjtshitfb.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtuzwtehvb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtomruvqsz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtyfeethmt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtycmlqejz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtapejbsna.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtneanubdg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtqepontno.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttyvfsytv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfjzwrugd.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtgvsepyut.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtsuyuefol.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtawrfhjpf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtpfcugtnr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtidjpkopr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtjitznuon.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtfflovwgt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtjmtekxed.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtvubhmzxc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtqaradmgm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtebelmmsz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gteiruzfse.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gttroysobe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtcbutafxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtbsoflrwi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtkgynbfpw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtfrhksqmn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtgvjpllcl.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtghltfxak.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtsmolozzg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtqnrjipwt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtocrjkepl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtdaumeple.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtziqoqmqf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtufzpiipk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtweokguyi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtohofyypb.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gteyhfljpo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtjvayvakv.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtzdobdsrj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtxnvsksem.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtumxgnkvy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtmcjqktcf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtofsngwxp.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpyqogocg.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwbdnqknc.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtofpqyrjo.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvmzcwcdi.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtqwmtpiwe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxjvbybkm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturxrzisr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtoodwpeuo.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjstsbpzc.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrwiytbdc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtsjirryfb.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtivhlejkf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtszqipfgs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnvihnhb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtrkilcayi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtdafpjktq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gturbubxcp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtustcybmd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gtkerdcmkf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtwautmuec.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtkeqsixzg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtnhiqkuyy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtdojtdugq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvmcdzw.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtbrxtenqc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtatjagzdd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gttvbyjdqu.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtlvacobkr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtxdbkhixb.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gtmytlzclg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gthsduldpv.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtqhezmqsh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtcpyerdpc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtgekyngbk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtkfrlhyvc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtwaplkglw.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgxmpfypo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtaxyniubk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtsveknjom.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgnqynqom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrxprsngq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtejvcimdw.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsbbmpow.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtkarscais.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gttmjvlzhz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtlmdyviya.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gthpjraznu.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtdzselqwf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlbmtpreq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtnafooshq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthnqkrfjq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtolezzvpw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvvdiuco.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtalwahuvn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlmqvwavk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtclqqphnr.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtfqjtesgs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtnfqwjyre.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtdjejbcvf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gttxpedlso.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtkyjppmlc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtajrmtyvd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtdyfeimbp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtcrnuzima.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtwuxlnwsp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtutsvwhbf.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtizaptfib.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjshcmrty.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtwafetboc.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtkrfiznoc.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtceofsoag.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtcyqefdon.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtctdrxouk.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtdpsfqkud.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtbaqgsdbl.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtwdpxixjx.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtecltgnhe.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtvgwuuwtk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtslmrkhvw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtyjsdwise.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtvzqfogvo.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtvfoazdpr.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtactijvbt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtmttuible.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gthyureyzu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtfwhnzuox.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtxoiriihe.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtwmkpzpqz.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtjvbdxlqa.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtvtnxmlwj.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gttpzqpddm.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtrgxzjfgy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtnhbxldap.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtveceyovm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtysfmxzqv.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtmbhbuazq.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtrfafwohw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtdswfahxl.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtuocqkoxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtshaxlopx.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtobvhkxwi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtmqyewvqw.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gteskehexr.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtqmfkaxbx.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtzgyiwrvs.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtfvqgpacg.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gthzylbnqh.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtoybfnfri.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtevxpjhzp.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtheuetqwz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gthcenndco.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtgpfpfjxt.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdjztuqmw.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtobubqvej.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtjohptwva.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtehmmdpws.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtpjsqhlmd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtetspqztz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtxintyenf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtjmmdrnvo.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtcpimkpyt.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtogzmdpnm.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtoowrhplh.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtvnjkoxqf.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtxvspojph.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtachzttag.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtxgoeshwe.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtirvwhyjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtsgekjiza.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtmfaeoybd.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtfhodxbhz.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtogutzhpn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtzmdnzpho.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtzobvihkw.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtphwhvhdm.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpagtpggk.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaidxgsqb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtwvkjryoe.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtgbbrfole.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtdumwkcxi.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtspyobtjy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtpckstdzq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gthzahjhox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtgsjggxxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtormcflet.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtbdbmngro.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtazzvxczl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gthitqdhwn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtgczqotob.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtzmcymkrp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gttrabqkhi.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gtoalvpmsh.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtzxglrppw.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibozmpsg.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtjbdnedsc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtzjmgtgof.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtvbcsvpco.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtysqpqinv.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtfvpfqqwk.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gthzjihuaw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtdzhczxlv.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtccaapeif.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtdaifztoz.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtgghiamxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtygbebgww.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtrwotuonp.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtghbwadcs.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtensntwhk.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtkidqktvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtflgsynxv.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtnrcdsdls.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfrfbvyje.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtgetpvcwe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtzgkkruuh.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtpubyggkk.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtpcmwxytk.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgalgyamt.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtpfohpwvf.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtjikxllkb.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtovoaupou.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtjjsszenk.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtaqcamnth.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtypgvufxy.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoedijjll.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtzjjnnuzk.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtyypqrdoh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtwdcgnyoo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtggtidwad.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtjkxrcwxx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtlgngjlhq.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtyjmpyvnc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxvzxtnv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeyqscmv.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtoesicljq.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gttwikqtjt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtgobmoxos.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtgxjfavav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtomoggqoa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtfjwmqque.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtqumggjao.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtdvxtvjip.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtiuesmovq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtryahygku.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtryuxlobu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtcbrvlhcn.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtszyvfphc.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtkaeeemko.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtznvcsblf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtinmgeoce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gteekvsynu.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtqkzlbdly.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtmgrqtbqc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtunvqtfmj.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtixwrfrlv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfzgxfgxi.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtzabququh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtvmturoqp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtplfxfxxb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gttgevcjzk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtxjdficpi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtztmdukqg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtkuuxtjes.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtgcudviss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtpvmljkkv.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtvzonnxhv.html


<!-- 参考信息 -->