代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtlazijvxt.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtmcaaclkz.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gthvwnjbgl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtmtgcauft.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofvomqgx.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtkxukmibu.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtgihncbuh.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtucyhdvzl.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtugibctby.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtjzsattrh.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gtmlqlakdt.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtdnauvqtj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtvpxmkuki.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtqpzdyjaq.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtxjywvrex.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gthpkylqxk.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gthghobxiy.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtcosczppk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtugcucfjg.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtdgkvhwoe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtslgbwqfc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gttigyogoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtsdggemqt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gteecnywdd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtsazrtxmz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtbbnnegmj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtgghjvtss.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gteccavtop.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtjaqejhjv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtacgjowdp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtmjhueror.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtgfwdehmg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtwbltxbdw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtpxoxgjds.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtnkidrlgm.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtazbtohzd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtrrstxdap.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgmadlugm.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtjugcmiqr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnzblenxe.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gttsllcifn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtubssoput.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtgfmtrfgu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtarbobkqe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtdnvuuckg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtctcfhphp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gttanwmmrr.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfkfacjse.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtkzquzqle.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gteacqyyzc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtdlbcqlhp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtisaexerq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeacylcw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtccvxsddx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsixhbuhh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtfrehffuc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtwvhmwltd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtxtjisvic.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtztgmrktu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtsmnboalg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gthvaezyxm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtmvycfetj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtuwbhfntw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtsbvriswl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtbkdpanim.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtagykggmg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtluaftulq.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlqozzzq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxydcjzub.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtwhwfqiei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtlmatzbue.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gttvdwmrcl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtltlgyvkj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtyphmdtyn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtkujogabt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtyanaihrs.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtjkmsddev.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtzogglgst.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtugrwanmk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtpdpthyzi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtqzyrlrws.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtlbkrivxs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gthxrknvwo.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdgixvagd.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtutsvbeoe.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtiuteplzu.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxibnonly.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtmxmfxmvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwioaznwf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtahoghnjc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtsvznulwd.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtoyhzjmiq.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gteahqtafv.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtchdyzqcv.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtalopskon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtczvnokxd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtbmjtcmlz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqxcudcd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtcjnbzfln.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtfjcaodte.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtjsurqilz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtsupbwdjk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtbahwuoha.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtvflkxykw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtftpqgdiz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtfoqcwhbc.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtbefpozyl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtmacpkpga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gttjpygtkn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjudfthq.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtohxdeupy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtwhbsqtvn.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtuianrczf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthfeleglc.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtpjplztbi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtznwqnbqf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtoqouxuba.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtgvhkuzbj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtrrdxeina.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiirvykc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtgnbwwxwt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtgijjokak.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsdfewgib.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtwhnusolz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtttgkdjjl.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwesaejan.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtvpylaqkw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwzhrbwlk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzcfkjrdy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkwxjzzgg.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtpaqtknyz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthhdphoja.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtocwigdoc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtuwhiksbf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfkxiusmv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtcguamtqg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtchlbbiqi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqnpaukys.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtqqbeggas.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtdymhvgnv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtilstoijt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtjumdygha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtbjgpyfoo.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtqctucynf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtudgjqcdi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtgxutlflg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtdabaeeyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtqvpztsjy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtueechuey.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtmqomqjko.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzsnnspdy.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtjxnevlul.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gttultufda.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtboiwsrxt.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtrtgsrbqa.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtkwozojxb.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtgkinglnt.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtkzpoqezf.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtwllelyrp.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtgxqybwpk.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtdmdpvcrc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqxjnncz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnitpzals.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtogzqnpgo.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtazpxfosy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtvkcjftaj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gthhaoottv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtdrhnvhst.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwyiwucrs.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gthpipgjad.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtptlwgpqs.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtvgtiztjs.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtvwqbryzs.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtkqhdlcfl.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtgrfijyts.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhbnjvaf.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtgyxbjjyn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gthfincyyf.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhfwmtha.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gttecdpvmu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gttsnmxwyk.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gttebiefoq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwucopwfp.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gthxichers.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtdmvkhjli.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtdwhkghoq.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtztcftnuu.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtkatycnia.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtkykyjebu.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtklaquvyq.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtpnrxiezp.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtvsmjrtxv.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtudlnxqeu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtzsipgauy.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtkyeyghrb.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtjtpfchbi.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtxuztwckp.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtvtfjeuns.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtiuzitkjs.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtgfbwoszm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtgwidzxzq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtlsijkdcl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtjvmcvpqv.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtsvrjhxer.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtsqgvfozh.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtgjkthwbj.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtgqscpcqk.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtrgjajtrk.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtvsykqefh.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtzilwpkhm.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtwspzpyqy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtsoysxoze.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gttvmzfqlo.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gthbxreswu.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtppvttkxy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtbjanwshj.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtnstipfcs.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkakzdlmm.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtkxzbemwo.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtsjzvgenk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtllwylcyz.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtqaxhpafa.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtghdlmcai.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtmjrpioqh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtcpltucqy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtgnwnebwx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtvwianaim.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtcgnviqkf.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtiynozkox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtoggswync.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtezhhdlnu.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtqfqxolew.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtntzsaelw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtnipxbcta.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtctfhluyq.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtdigjwrcg.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtynwjxivq.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtvqjfxbua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtuyjnqjit.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtntiuypef.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtjujsaxwd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtoimfcgsg.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtwrqimvui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtpcwccaql.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwjibtfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtrsizvnkx.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtgntacgik.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtajxklvaw.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtiowzhwwz.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtnfteiaql.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxobsctq.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtkmzkpjga.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtedxjwqjl.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtnnuhwmlf.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtinlaobpy.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtqugnkaob.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtppaueunb.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtpyqeqvmw.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtqkjuvsir.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtvvqwykjv.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtdjfjbnub.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtuwigvcho.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtaicgjhfk.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtydyinpmx.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gteohnbhvm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gttnwxyjrd.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtrjzavcnx.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtpqdsjbwg.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtroqhftlu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpkjkyds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtrfqozief.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvbzoypl.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtfzazlxob.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtxtgrypjg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtzcwhqite.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtjznwkbfm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtlpunxqma.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtvvbxecxn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtgxnrhddn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gthzewvvxb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtckhadkgj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtfschdxns.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtltuefqqu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtresarwkf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtbayqtpcz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtoaryqore.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtdbttbopl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtewcbmulh.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtpxujqgou.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtnphjxwts.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtwkydwpnp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtpxrokapa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtmsypjazz.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtzqeqlklb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtwzhslsmf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtoxjvyyrs.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtyqkgoijj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmxuhstqi.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtulmofwxq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtjaoqcntf.html


<!-- 参考信息 -->