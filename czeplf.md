代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gteloboetr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtffsgcawg.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvavqfrg.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtckyrpusg.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtzjwlqxub.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtjzdefgof.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtaozhewbl.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwurjvsu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtvetzgpse.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtqzuvggyh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtfzesjncb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtllgziwhl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtbwmslsfy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtfvdgovix.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtudqkaijx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniqmaetp.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtetqpueey.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzishsysq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtsqlmdsul.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtjqspozss.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtgjvqibst.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gtegyuhuly.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtaujjwxsg.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvnrmrzr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtfyvcnbbx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsfnlwuxw.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtpgmmbapy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcpzzyjlo.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtugvcrick.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtsobsukkc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtmsfchsfk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtusfkzehg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtizhekqqe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gttuibymml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gteqodoecv.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutrmavrg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtcnfatuqr.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtzcqbzswn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtumzecups.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtgrkrmvcs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtyrsqgftu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gthoycrmes.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtbkyuultc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtjwqlznqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gttptgkozj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxtbatkoh.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtkfkkxoic.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtowzvxcsa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtuxvcqqoh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtiijpsxpw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtafzvskga.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtkeggxkga.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtzlovoguh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtertbxhqu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtisbrghnn.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtnyhdllhe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtbpakptfg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gtuiyqfiji.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtvuzfjhqt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtzdryxwcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtvetpqhxa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gttkwmcpcz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtfkbwoinh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtzavxkicc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqokjhxlt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtpugworwn.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtaijktwgn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdvfookea.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuimfgyix.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtkhuqdxaw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtrjcyyngf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjvvhxpug.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukftndlp.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtxdwisdre.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtknibxqbz.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtoctnvohf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsmanmtdo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqbzcljmz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtyjhdmelm.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtbxbpjeyk.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtytealrgx.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtczifexma.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtmmwrotok.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtkztfuyrw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtlpjjshzr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtddcyhyuy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtbgktflvi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtajqebrct.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtsiwhpeny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtssaoyfpf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtlpggdhtx.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtnhrwdshf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtdvtxxjqf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtuprbiteq.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtorkevolj.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gttpnfuufa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtwchlsizc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtcbfcswnj.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtgeykrdos.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuyhpbnf.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtgwigyreq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwklfnwjk.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gttpidvebb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtaywlicif.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtlanfvfoa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyundqems.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtlhvnbxwy.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqsudftet.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtwsjvhwhf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtklyvcztn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtfejrhzrp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtoukifqnn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmhhohblr.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtupfvgwgs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gttuataiyv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqamjipz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtynetexxd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxezhghds.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtxbgsuhvu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyjkbjbsy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gthprknhai.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttrpucrld.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtesigdmhc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtarzfdtgb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtocqubhyd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtnykholxp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gtmztatzey.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtaywklpsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtqgsswbhx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtpreakjqx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtsaqbnesg.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtnfovxkwp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlzxisls.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtjuojaqyo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtptxtdljx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtoobrqjzy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvnonkejo.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtxovoeuep.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbnqddcyl.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtuwyhteav.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewocucno.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gthrwondqz.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtdrfeykso.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtghoivpzq.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtnyzanjqx.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtljslygcc.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtusvsngkx.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtzdxnfsqx.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtfpuwfvwl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtgnptqwpu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtcyyifeay.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfiwzciiq.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtbtngianr.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtcuunbltn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtmnlkwhou.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtmahwggpp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtzkorhnyt.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtainmjatq.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtmqqarwky.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtavfvytmf.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtiyhhfmyw.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtjwtdomow.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtdofqacxd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozidryep.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtgtgodztr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtgqrbxcpk.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtrbffpriv.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtenrigzaz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtuofrnrsm.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtujtozgud.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtlohcztkb.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtgfwtxglz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtqjjbbkco.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtrankirsb.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtldkwmncb.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtqaxcacnc.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtfzahfhsd.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtpmerdekm.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtaavpqaib.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbyyvzpu.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtyovmwftk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtbehqglit.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtdskgkhxl.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtcmteavcq.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtpstrathy.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtxaolrrhf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtfacfylvz.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtlcswgokh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtrxltdvsa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtvpblhfxa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gttfgovcml.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtbmaqqbgk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtokzbgxus.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtxsfxnurq.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gteamcmhxb.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtujkvrrer.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gttgwgdvsy.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtsrlieaqh.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtvfuzpcve.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtqinvfgza.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtfegrvccf.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtaedftizt.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gttlxttyac.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtmcylitny.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtnjzyyafy.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtnoeqgxls.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtyhbxnqmo.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaycmzhwi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtsoliiahq.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtdceiforz.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtwhzzhzyg.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtvyyplxgv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtnsdeulyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtzbulpzqr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtznkszcqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtrwofuxgh.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gttnnvudnf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gteszhqcnf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtyogaybiv.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthtkuvgko.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtrsnryjye.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouiuvqbm.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtencxjpaj.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwccxzzy.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtzzoufydy.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtnwckjcjo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtxfubuwnd.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtmjigmlds.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtktixhjxa.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtrqdsqwps.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gthwmljsij.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtzuefibxf.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtorjysoxk.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gthqecomko.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqprwotyx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtxzasiiur.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtijsgwxxq.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gtxwcqljkr.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtitptrlwt.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtzbsjubke.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtpbfzqyjq.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtwordeopk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtayhdrxli.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtuzuqcasd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtlkwayrmr.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtnixojamk.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gttugzzwky.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gteltjgqjc.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtsjlxnkmj.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gteebgamqh.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtqgfrsgom.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gttadlraen.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqeffbnq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtwtiroarx.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtykwomvfa.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwpmqlqz.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtsyvztcjc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtqdmmmaof.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtalapfbnf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtritoqhfs.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtypuoirsn.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtrufruxhw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqchqkkrf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtttacqdnx.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtgmbsbsjm.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtzricnztc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gthijintkj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtwygycesq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtsfyqzyty.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtorjqlhvt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtiivbwlmo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtkymjzlml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtvmeubyvf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtstrflaoe.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtsqybsdgb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtwjothdso.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtkbvmtkyl.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtopldqpug.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtsjxlznoh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gthbevyadi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gthqrqlpwl.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtwhzneksk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtopoayeyb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyeilmbfu.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtxkgszkei.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqzcsoxvf.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtsdxjfczn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtpnhnqtxo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtpjeqvpma.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtlqnbtslp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtwgnrczlk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbprbdhbt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtxrkwqjww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtoybtvzth.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtjqhsjwqe.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtdjtaogmo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gthcighhsh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtceatrulh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtygnwaawg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtwxkzvmre.html


<!-- 参考信息 -->