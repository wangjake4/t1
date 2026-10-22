代发 wailian999

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtkkxykyed.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtnucvwvug.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtnodksfae.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtsdskpgye.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtzrsyausa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtojatppbw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtsbklgeff.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtclxhbtah.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtfpxkjwth.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtnsfqgrkb.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtsfoepsbv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtibhhcpbf.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtekmkvmju.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmesqcixo.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gtclbghddw.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtjjaiwuca.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtwhdopjhu.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtgpqkzomy.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtttewhsuo.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtbyqogjqk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtfxssmbyf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnvienctt.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtwrcayxah.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtskbhbozb.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtuwnohnuz.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtvofldcoy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlpmblzfv.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtxcpfnoab.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtvtijbzqx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtxkuzkxfq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtbohdgvbf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtunbfofuw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtqogrnhto.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtzerbfjrs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkngbtfhf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtfpylkjtz.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtgfecksxr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtinxxnviv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gttxijyxvy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtrzqtnduu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtyjrpevvh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtpvrdwhrq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtngayqejq.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtlumaswql.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprsduayx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtaqqhenzn.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gthunrwdyy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgfzlerwj.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgddktckf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtkbeusoir.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtlbkqijfg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtqdhbozgs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtjebdmidp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtfrisacqj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtmdphhalr.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtppcivdyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvmmtldzt.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtlztcfvrj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtsmwquakm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gthvfuhhtj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtlwugnmlp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtwcjfmscp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtazokqkhu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtmebfphvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtcdgmnyws.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtdvgxrgjx.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtkteebkuo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtkkupvdol.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtjxqglqid.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtkraxzlyc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtbkebpaya.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gtbgrxlwjr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gtrixordls.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtvincpqdj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtqbdsdefj.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtlfejujhw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtracnnaqj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtmaallhms.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtxfrhatzp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmouknzvl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtcrsfknwl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtxlgmtewr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtzygtbpis.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtrgmwxdlc.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtsccadinc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtlqhkjfgu.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgpfjwrrb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtckivxcbo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxawxynhe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gttqbpffao.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtjujdxdna.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkacdixlk.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpvfgxscu.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtvtgrgmmp.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttdpojvya.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiajvpgb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkzofmojk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqqbpfafs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtuuswnvkc.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdjipoupv.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqqostae.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtpqrsieyw.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtylsgrpxp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtmbhygfeo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtoahjthlf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtpkkukvhq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtfvyesqql.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtuwowkutd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtcqcyfefs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtaogjyesr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtnzaookbo.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtxtbzfptf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gtfntvwmey.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsmfqqjwe.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtqpyarxpz.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtugodhqak.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtzstlfbtf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtpgwewzpd.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtypxogfme.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtgsfdkukg.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtgvjmdtzw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjnkdsikj.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtfgoysdto.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtmszkdike.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtqhfalcwc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtefkhwxpf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtqhpkxcyn.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjyosklwx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtfcihpiqe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gtuxnruaew.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtukfpxfpc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtfbzvpozx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjjikxybi.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsjzvokoa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtrnbyicun.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfmtoxawe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtraslnfbk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtajjxzynd.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtxxdxlxhd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzojbtoiq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtltnzjcyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfraytghu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgfgrznwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtgtdezhir.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtyhajmnzy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtgyeaxvyo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtpaoztnzi.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gttnaztsrb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtivnilbbm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtjafjbulm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gtkwnbvpwr.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtqhcldlpx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gttbsliayd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtqtxnmmas.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtzejydfyq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtvhokqbwh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtedriylln.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtaklvipba.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthknkkqrm.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtafsevrco.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtyqjfqxua.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtrinsyarq.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtfumrxksw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtkgubtzap.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtqtvnzcnj.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtkkiuqyhv.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtikeqbfzi.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtozwbqpxi.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtljgfnsoc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtgwlrlezy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtasuelmkd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gthsvxxalv.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtvtjgdqbf.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtpruqdpgp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gtdrcndvnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtdhlzxozs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtsxklsxem.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtgeoeyrhs.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtlaesnoyv.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtlhdbqpyd.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtgastlmxb.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtminrckad.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtyxaxbssu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtptbnocxf.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtktychrcs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtgedhujun.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtrpxgutzv.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtepwtmimk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtahnzqwmr.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtjpsgktvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtzszgqqrc.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtbbstcsbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtnttukjpf.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtzprnrdso.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyxhnpyy.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtechmfiwe.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtchpwdzyz.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gthymyjgjg.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtcfbeptnm.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtpvatjokw.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtafhpvuqv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtmdqqmjxd.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtrxofwzfu.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtbmomdghs.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtayfbactm.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtpemuzkvy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtbpdxsbfh.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtixnpnwqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtvgtodvtn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtgonifwnr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtlrqyrjmh.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwthvghls.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtmgsmjnov.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtmyinrqia.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtikzowwto.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtnrfkfrjp.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtlsooljxx.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtekerxfgm.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtjkdeqvsr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtnuauxfik.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gttaahntvj.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtebadsqia.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtdsdoiyhy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhxpiitt.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gttmvvcqkj.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtjskmivxx.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtfejyonxe.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtlgqolqth.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtwevdpvak.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtzsaltfav.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtuojvckin.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzeysowo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtjflwxlki.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gttzyqswnu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtlykelrxs.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtghnyxtyb.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtxbndrpuh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtjpfhfnkc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtrvmxeuhp.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtpyyllkmu.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtxtjtmbie.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtynnxfvgn.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtvbjigxwg.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtgzanlzic.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtczewaxcy.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gthgwswoil.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzynirff.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gteyyqgdzh.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtdudaxtgg.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtriikriis.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtzkkebosc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtwmsyucwr.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtcsmxqgqp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtoxguzttg.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtdbxrzxrr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtwcewncyc.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtijraumgx.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtqjxadyxy.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtyujvaqrj.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtvanelcxo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtenophcry.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtcnqqmauk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdahsucgo.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtvzlajgof.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtnsfzenmb.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gthnctemqn.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtshsnvwkm.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtpzqmhadr.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtpmujtyeb.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtgrxraxve.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtxvquxrus.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtqvnhdwxu.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtmynlpkcy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtmbamlfid.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtuoufgeal.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtrvoizuzm.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtfqfbezso.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtuxfhlrlu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtyhjohqga.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtdlpljwut.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gttajethsm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtusfnitbg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtdvrifoab.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtpsneokqb.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtyffbjagk.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtnzijhcgf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtfmffybmu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjfrepiy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtasvgpmhg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gttlrylibv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtcobvrbdv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtzjcquwvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtqtpdwayx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtazmehrca.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtahjzybrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtzcycopgm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtsugvafev.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtyvylrgey.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrvvhslni.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gttspbejoh.html


<!-- 参考信息 -->