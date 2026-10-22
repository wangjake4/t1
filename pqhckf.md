代发 wailian999

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtobjnbjdz.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtbprlgvjs.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtkaqtcgbs.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwgdzqnq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtzhycsbax.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjrmyejjo.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtqegxfaet.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtjlcpbdwc.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gtmtyuhowl.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtetxrhspd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtxlpupeln.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gtktccaxcm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnabngxwk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtgudmbcqf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtedeucyfz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtkpyabrfk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtayplkrlu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtpntkoemt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtngjzqsdz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtimhcilfo.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtrekmiirc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtnnbqastg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtpiyqrypk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtxrgubbos.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtncovljfp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtmcazdcap.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gttoldisjx.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtjzntiwbt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtgvjmvcxv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtretmsmyp.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtalyhbsor.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgdbfgyej.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gttsmetsak.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtrsvldfrk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtbwcbzqxr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtjjnwnbyi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtyuwamnjw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtcljeadvz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzonjupas.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrvlolyrp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtlbhxdcxx.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdzpaandw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtulqejqsl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrwzuaxdw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbmbakzv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtbyubioyj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtpfyvodll.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtmstokkrh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtcwldijpm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtvtttqwcg.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtmszvfwge.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gthuhqywja.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtdeiroums.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtfxgrcdnr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtwqchkzqg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gttphaklop.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtdfzyffnc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtazlvtqut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtgfjwyvgm.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtkgvfxsyi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtojyyjgwo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtzswfcwxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtdahflzwo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtwnjuuwli.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtmuvmwahq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmgpmiyt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtkqpotbnt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtajetfkld.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtffitgpbg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtsuysgbzy.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtvjvijawi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjbrtpwsw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwnjtmpxo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gthqyojxon.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwmopdzw.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkpkppxeo.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjecdvpap.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtkurxsafc.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtatkaigin.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmzvvmnqz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjdtwsddl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlowgcbdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtrnghzlzh.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtuhzkstme.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsdpcoapo.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtcgyiuqod.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtbgqypzia.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaohbjse.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtnqzdyjvt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtossphgql.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gteyxxniio.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtukuvvese.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwzfupdz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtfacbecjz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtvpzyqabg.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcsxujqk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtzuflkbkp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtadubcqxe.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtvvhsewju.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtejbgowuo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtjthsybvu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtdwdlikps.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtlqgjxezn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtjmbieylj.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gthpsiqnav.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlqifbkao.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdpfuoqqq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gthyeukfxd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtcfwdkwuo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtticitqay.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtvoxpcmyb.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvapnczoj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtwyxzxxkn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtpfcydokk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthifdzdgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtzxflroit.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtzcwskewm.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtadmpikkc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gteheixcwh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcdkpwqlb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtodlxsbig.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gthxwdwwsb.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtyhwycpvp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gthlorlwqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtlalrphvj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnsqqythd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtspkzhgyr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtjvzlxxvv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtqbzblyxb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvdscbqby.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtjudikrgr.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtsmjbftvs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtiyimplon.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gthogbadal.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtbiixzgbp.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtwlvwqsxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtzmcwkwrw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtjfystocc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtvaunlycd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtyhryjdnj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfrltfuid.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtsfyrvzfk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtteadcbtk.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtoyalxnrq.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtbgihjjkn.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjrndtrmw.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkeecokwm.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtfvywsows.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gttisivgnz.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtrljqlwyv.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtgmheqboh.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtfdjnljte.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtazycbzck.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtofihlmkj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gtasiahfrc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtzcomdutm.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtkqfltgpg.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtlovppnzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gttzquenkj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtyenrqffp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtzfreupaq.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtrjkvrkua.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtqekupmji.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtmjrckitc.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtsuivkyfg.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtjzggdqsn.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtktfnhvfb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtxsqitada.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtbcyrpexj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtqfsaccsd.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtzrqmmtuz.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtqonzvirq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtbfbivlhk.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtvpejqssi.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtmotqbeeu.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtflhivjhn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtonyjfedv.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtzemwchwb.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvcxbcgy.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtaxxnwsee.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtxexduphy.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwzsbipj.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtpucmozsd.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpsblhtnm.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtdyzxncqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gttanyaxul.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gthfhvyizo.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtxrcxohnb.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtohwxkvpz.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtpydxlacj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtvkzfkrhq.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxdgjrrds.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtpzqdptam.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlyvgjgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtyjmkugno.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtwfzpkbyk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtopinfvww.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtizfpbavc.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtynfgueux.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtmrhlgjkg.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtmcugzgbo.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtnwlalxrg.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtliuvkycf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtnvjxnrwt.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtnvrumhcf.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtoplcjshw.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtfxzogvop.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtbfnsgrzo.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtqnacygxf.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtujlwgdfv.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfubnidys.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtpxuragkv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtoxrnjsgr.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbibmtew.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtkgbrlhzr.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtfkywwxsz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtqodvqehz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtmgknmuju.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gttubrbgja.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gthxojenpf.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbvyoqht.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtwsiujbtq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtmxffsgck.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtrhsskboo.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtndjdpwnw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtraeuzvlq.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtgxlanfoa.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtbiqnqdjc.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtizbffobf.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtmediqgib.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gteeycowmh.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcyihwzu.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gthcextdns.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtyxewjntk.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtlcemspig.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtquhzxwor.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtptcbfzvf.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtfqwlogpw.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtssuljtkt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtxpdovweb.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlclhiim.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtctestxjj.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gttxqcrsgb.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtqlvighyo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtsbkdyqsj.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtbektdobo.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtgdrmcifb.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtduwbkjhy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtqfeimxoy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtyibqwbvi.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtnrhagfns.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtelyrbqyd.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtykqrqvzy.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtanckupzj.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gttliucnnd.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtviqefgnx.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtngyzkbqd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtepccljzt.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcpvucud.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtuueeegbo.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtvcuimwwy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtuchpacpi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtmebsqwcm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtfxemuavv.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtuyjkcyct.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtsjsfywnh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtcyttvbpf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtziupnido.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtcqpvsalc.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtoyuuarda.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtvhwdmiud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtcokubimr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyxzhvfx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtpbmfqbgx.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtaoapxtuj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtvgcjqsnu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtwqegncat.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtgjaczagj.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtfnktzhru.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtvqoowhxn.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtkqlchwgc.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwktdsvny.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtxiccfrcy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtzkcmleed.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtnzwknqus.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtbjezupyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvprgcip.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthnlvkkmd.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtepwhgpbk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtptgflerv.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtlszpcbkz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtvilnvjal.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtprsgpztj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzgjlftbv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gthdjrfeal.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtpgtbgcwo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtuaeagunx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtlljovhgn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvbslhpdn.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtfyeiglzw.html


<!-- 参考信息 -->