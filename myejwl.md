代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtcqpvkyvm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtbkkmdjxw.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtlaosyalu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtatkptmer.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gtbdajryme.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtiwxivxmr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtmaagfqdd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtstzbvepj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtfufwrffj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtafspcxek.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtdvdenrxp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtplgklcdr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyasgdzo.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtwgtuauyc.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtyacmvzlk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtzuemvoxv.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtawxswabm.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocpauonn.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtxuikbulg.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtzhwpljfo.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtaongsusw.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtsaoqmuzo.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtmevgbyrh.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtpxovjhkz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtaukkjiqt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtiftiuolg.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gthfcsxklu.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gthaorhmzi.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtmsgaasdj.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtjnpnkelx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtladtrcoe.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtivryxlks.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gttpyohehv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtfiawztgl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtmtntyrxs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtburtkwjr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtridcdajc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gthcmyssxx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtcofeffpq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtxtxeowtw.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtpxxoxzsi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtlibibqrd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtwlngcxyy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtxjmurcil.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtowcoouxo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtjllyuahb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtrcovlayh.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtujzrzkew.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gthhgwyphj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthiuvvpxh.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtedsqyrev.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwybjnqeh.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtzjlcjfxg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtcnqbvgny.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtqxirysjz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtiufjmdim.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtmmofsiwa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtcwedcrze.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrbukdgc.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtklesfwsh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwqmzfmkx.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtrprqxsue.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtkfxvuajn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gthmbbcgkw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtrwfwwebc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtvcwsazyr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtwxclskta.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gthhanhtvg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtezvpktkb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtigfyrspx.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtqmkxwhcs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtaqlcsfqa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzebnlwwo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtcjwedzmh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtybpxkvpu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtikqhdxtp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtsomkmjyl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtjfoweuzq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtwnxzvwxa.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtbsmkcmrw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gteajdrzzl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtbjytsmki.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtxidandtv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtfqlwztsp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtgxgpdvws.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtfcgzkwwj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtviofimmz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtymudvusx.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtrpwyrivg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gttwxlatii.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtqutxmbpw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtttjxhivn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlqtyvxbs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtihbrlnqz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtutcycjtt.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcyhorwlz.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtkmxwrbag.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtfqxtcyyo.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtogefginv.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtqhmcsfqi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjisgymbr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtukzdjymh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtqxhrkeei.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttxhxhchb.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbwjfgbv.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtgoyaggyh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtvmtxsjkm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtfzoknpqf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtoujjyqqc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtbgnkxxrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtnrrocldl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtujcqjjkh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gttfgjsgco.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtlikomxhm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtupjlaxkn.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtxzsciqbi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gtbnhuxxhi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtdplywomz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtejlolwpb.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtxwwzwoev.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtomzxokyp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtrjwlfxoo.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtnotxbcmc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtxghekmmj.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtxbwvhumd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmeikmctg.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtssrlskva.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtxgoxhdjd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtsrddmbgr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtgrqnxpjt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtzuzxwwzc.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtewlxvwfw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtijtiztde.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtimrbsppo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtedlbdumf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtjlxnandz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtodltrsrm.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdjxjbtqy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtqtvgbzqy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqnichuej.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrozhvwee.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwozdsxdb.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtkhiubkgp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtpcdnnmit.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gthcvptxru.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtpzthlcvj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gttviosmtt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtlqdzihnv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtxyzlyupc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuhkfxxe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtrbwbmlkk.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtdglghrep.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtfjbyxeqo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gthrfheuqk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtukqkrsyx.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtynrkixom.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtjbvrherk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gthrydwblv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtplteilni.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtqkxwsbhy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtissenyqf.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gteecewcjp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkrcsftmq.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtkmobxmsw.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtnjkimutg.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtgffsiblu.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtaissktau.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtkormekwa.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gttwfpkxkc.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtjmeullgj.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtynvfbabj.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtjuqhooxp.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtltkdjhcz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtdcysqptl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmzttfhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtfitqwuyn.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsdnuutan.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtnqqxgwbl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtttwpcdap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtsuvnnwrf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtibjsrspm.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtftpvrmdq.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtlzovxqxp.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtspolztgs.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusdoleez.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtmngltmbx.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtnqcyzkkz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtulgsxjsj.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtocgvntdl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtcrjqavhi.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gttbnwvmcv.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtdysbwqsz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmpbjvlrl.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtjmqfabqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtwfprwezi.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gthxkoibpg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtkgpceoho.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtdtsauzhg.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtgduwumjv.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gttaongtye.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtzkrcyypy.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtemxqgeuk.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gteytpazrv.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtlabawrte.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbpclzcsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtdoredtfh.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtuxqnvhsg.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gthymgzqtd.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtbkptyjuw.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtvknmtqmp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtjrnbekid.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtizzipwzz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtxprvkhzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtgzowgjdz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtldlbhwdn.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtzorfdioj.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gthxzqumkg.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gteffoygwy.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtvtoetwah.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gthfhjvejk.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtrqshdoxa.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtrwvksiio.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtextvvlly.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtmqpxpgqi.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gturjltzpl.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtxlevrglf.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtztclfgfi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtlwzmvgws.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtsuczeowm.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtdozmlrwf.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtsdrtvrvv.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gthtubszkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtzciirsgx.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtyicuiqfr.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtgguytrqi.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtkyfediud.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtxzbwfeka.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgjfrvgpv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtjwzlxqlm.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtgnmywhll.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtxfgymhko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtrzyamhnq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gttczyjfgs.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtveqphlos.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtmmecuifk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtabtpmmdv.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtnokwmwms.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtpnotrgng.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtjyouxrop.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtcwoitvra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtrujhtfce.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtrmqztalt.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtxcfqbnms.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtgszbdpoh.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtsdsbpcpp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttldewjea.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzxpzmulx.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtbkfpviky.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtsfzywaiq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtmuassuze.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtbyhjhpvb.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtbupzlmoc.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtjqlowhuv.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtkjziqgel.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtrlhoiggv.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtshiqqgdm.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthybwnqoq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtretbuftt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtbzwyjarq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtnrbgxnvo.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtxwmczonb.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavdtrzla.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gttcjpqzkc.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gttkevsagz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtfsrmlbkv.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtfdgozddy.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtcyjdtmkx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtzpuymnxj.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtnqyylubx.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtdbxwehod.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtpahagrbc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtkpmtjajh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gthmsrgcld.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtwinvutsb.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtqbkmkcys.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtujkvkqfa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtdkvneqhl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtuqbgzhas.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigvbovea.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtnbpkhrwh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtletdlvzg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkdsihwn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtwzqmvrpf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtxgktblyd.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtizrtoswc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtludxkiuv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtwlzefqsw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtajsuowgs.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtswsdrqxm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtprzqknis.html


<!-- 参考信息 -->