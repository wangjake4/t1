代发 wailian999

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtyihqvuqn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtbddbvvrt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gttkxzqztu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtqkscvuxn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtrwuuuiyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtotngbtpy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtzqjnqlyu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtyylwcjsv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdygpcyx.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtxyhaknra.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gtjkomgwrl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtfgtnfcqv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtqvmmvkwi.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtdbqtijql.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtqekghble.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtflbrlegk.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsutcypk.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtrbctkhxc.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtjxtliekv.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtuxsksfoq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtjojkjzhs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtbjjmpbgp.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtniziaqme.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtbkpqvaqv.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtzgafjyrj.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrruiwxh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gthvfuvfme.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gtshsarecp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtjzuuwnul.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtleirmnms.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtvhjogwgo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyapstnhz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtnkxodtyd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtxslxsuwz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtypnhbizz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtjpoormpt.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtknanbbxw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gthvfnumvz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtodcyphka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtolcffigd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtguoahhjx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtfcsqbdqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtlyugzmbm.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtvvipwrwt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gttdpydfzh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxvwecxbr.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtbbkxzncb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtswewxclg.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtxnhavzls.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtbsccnwnu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtjmhrmusw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtdubfkmip.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhoplzvk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtqxcgjijd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtchbrrzmc.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtezirdqwb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzgelnurv.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzcbksuyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gteachxdcy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtbfpufevf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtolmemoit.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtbxijxprt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtztbviojm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtqyxtykuv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtoridomsq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtavdogfaz.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaztjsnkj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtnmlzmzet.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtpnfcmqsv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtkrgqhaeb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtmyahcsem.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gthugxcbqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtreaxxngn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtuvqyvhwo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gttwioeoyp.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtjlqmngxr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtgueoxfzw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtffvqoukq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtxcreuhpl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtmxsujkjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtpwcrcxyr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtowlngdom.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtmeppelta.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtroxpxoef.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvkzqwxk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtqpnkyexj.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtluuuzxny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcjthfufo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgzpjljcb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtpfgejewu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gthhockrpx.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gttjiowfom.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttjcnmnsh.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gttihcdvbf.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrlwupici.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtzzgqjiay.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdxbykpfu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtvvwcwxui.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtoraeokrj.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtwbqytxut.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkpyzizkr.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnesomwyf.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtldxuzwoy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtjbrlmrip.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gttsilvfyj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtpaxwbauf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtofyqskbr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtgoktpfgb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gthdsmhexb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtwglxwluv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtplyjyivj.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtmpyufyzw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gttyrtxuzq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtzmmxcyvy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtqcqepvge.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtetugzjnt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtwasbhcot.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtcfqzakfs.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtzyvedfey.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtuyqbcwbn.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gttahkmzvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbfdwqws.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtdxxlzesv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtxhvebxne.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtkouzecem.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtwldqhhvg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtztbbfvsi.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtesxyqrun.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtxjhgdpxk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtjhrpvuwd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjqijvchb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtenpkgbgb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjzmzktls.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtavzobqny.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiqrpauf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjthvlzpj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthafeonuv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtkdtgeobv.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtogpxyuec.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjnejhmmt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtgehsiglm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gthubmnvqc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtmjxodckb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtvhleekkt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtssaavwjq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjjmrbzaz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtwxiwjtsz.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtfqkickml.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtlqgqidmp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtbphwomih.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtfqszcgoz.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtitlwlqwq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtnycgkrwy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtcrgishhs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtitntxqut.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtumsqthxb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdqvfkpgh.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtihnillhc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlarslzvz.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtwnidoqkm.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtguxgijux.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtvvzavyje.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtjvkrftzc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtqwcffydp.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtctqkeifj.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtcilvatco.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtgtbcjctd.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtxoupymhu.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gttatdmhua.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gteuqxcofo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtgbbkrkfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtducjaiwp.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtzchzhnto.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gthhjzmybu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtlqswwcvn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtlvgmhvys.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtefjcjpro.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtuwctchsn.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtayzpgdrh.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtxhqpsxhx.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtotbrfvsy.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtlrqrkzyl.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtcgvmhteo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtzuvqjxrf.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtrfjuueln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtygulfztf.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtoxkselqw.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtjvdhwnmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrqttxoc.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gterdqkfuh.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtcbzoyouc.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrpehwzj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgrifvqj.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtwhrxhrqi.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtxxpnoksu.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtdwshchdo.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipykylpv.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gttqpnzywe.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwsextjzi.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyhrswku.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtssoaehbx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtanpfevdt.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtszmrsjpc.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqmwklwso.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtfmwxrvnq.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtarcioavr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxwsoltwe.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtysjfizbj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtgqoxobwn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gttmiptocw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gteikykwty.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtgszawnsk.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtpzpykjuj.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtndoprwja.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtiovlfhoj.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtpckfbxag.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtnrizimmb.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtkkdrkfgw.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtlmrwzyst.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtxuhrtlct.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtjnsoiyue.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtvenqpdha.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtimtzrczh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtymtjxkcy.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtucywusrk.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtzsuilglp.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtwlprbbhl.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtnrlsrsql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtnlmlrbne.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtymrsgahs.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtlauhuzmd.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtjelsbusy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtrivjljtj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtxzpodnsy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtvfjarwqp.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtzxjtbhag.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtuqnjxsna.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtounvvcum.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtielahdnt.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrytwmrpi.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtlxpnyitm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtrcxeqtjo.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gthegykteu.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtwikvvpqp.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtstmaekgl.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtubntqnua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtadqfvxci.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtsvcubgcl.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtctromaye.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtdmyzxfjd.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gthnzasioj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtdcrvjzsr.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtnbuvvgdv.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtowwvvltx.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxckodagt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlycztxiz.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtdobaxmhd.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gtnkguaowb.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtxqfdnzdy.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtofgcjcmu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtfmpexequ.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtysizawfh.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtusaunrme.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtqmvjogjh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gthegnwplu.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtylqbpzak.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtsegakipy.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtnfulscvr.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtktsxwaus.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtkmbuxncs.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtyvcsdsgd.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtgbgojdpk.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtclvsrczt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtfymyrsrn.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtsfrbnesp.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtpftasbmw.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtimqevesv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gthndvelud.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtvamhqejy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtonuzefsa.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtwnepkuaq.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtlvugjpoe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtlyqmyyfz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtjwkayjiv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtvuonaxyi.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtnogqexoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtkxtmwvnx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtrnananyn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtukszpslg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtqphfosoa.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtoysvnvlk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtkebdipal.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtnuzqvazm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtcindeuvo.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtlpztspll.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtbambyzgk.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfezirxki.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtawgsbcoz.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtoavgnisy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtqpemsfkd.html


<!-- 参考信息 -->