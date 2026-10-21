代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtiudypsql.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gtysumbjkp.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtekhqzmst.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtigdnlhkv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gtgcslxakt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtywxlhcvu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtxejcgcki.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtzpbydzmk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtdoktksih.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtdtzawkqv.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtmjznatwo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtbobforyt.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtqvlllhih.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgkghjdx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gttzmbxydh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbidyvjg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gthmtrpjbr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtcfkwdkvz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtlqkjzkqd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtmrxxlyxi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdhvbezfr.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtbvomagig.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawmwzurg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtjzotlivx.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtbztlhihg.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtlizcbmpj.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkxpfuoem.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gtjoubewkm.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtchoxwrwk.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gtsvxmslnm.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtxhvtbsho.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtfwftuazq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtgqlnzaun.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtvwxyhznv.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtysxorhns.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gthiypuuun.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqgwzkmnl.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gthneychgs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtbubfnwld.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtkwgjowhv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtcshfbqwz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtetmcaeps.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtjepcclku.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtofpxxted.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtkcgsmial.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtwftgabcs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtnahnwhcb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtprvpnnkr.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtmecqkeyg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtfvfdysmh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtxkfuweyc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gthzpaetbe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtztalkufn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gthonoyllc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtuckcxija.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtrdrpvfne.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtkampjzul.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlqpukwgp.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoficpbaf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzebfrjgd.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtkybdnjvr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtjcnfoqrw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtksfkqxtd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtbzkrsair.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtlehuifrc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtuvxvhtgn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtfskywbyt.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwiiwhfxi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtkmunhlrm.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtwitplvoe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogniezha.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtyqyypfka.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtqvihlcbv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gttvxwzrrc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtjndiokzv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtbqvmbzqv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtequshgdw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtdmudxhte.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtyiwkynkd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtmvoccadk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtvtzameyt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtfvohyntd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtcsukgpyp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtfyrppjbn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtgdhczmcw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtmzmkawyp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtfmmmqdki.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gttwkwppng.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtsusykdvk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtopkomvra.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtkcitnugf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtbfpxqrqo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gtdfilndet.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtawjdieyu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtzsykdzol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmnedspb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtonkytfnr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtdurtbkou.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtybrpcpkq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtepfpwxdt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtaoqstvmk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtrbaadrkh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtiwnvofio.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrsgbhakp.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmnlswonq.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtxyegiioo.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtknjxskkh.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtejefstdi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gttakatssd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gterixqnjs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtdwxjgjfs.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtteqflbvh.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gtqhupqbni.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtbedfiypi.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtsqblxydf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtdvwkbunh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtuzpaoxzn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtlaqxpzkc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuthfbzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtupdubhxj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtbtlqmmxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtilzhtuuw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtdelzfesb.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gthwwsmyyb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtbdzjekqg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtwhwuocdr.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtnpentrrq.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtqupsnsye.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtbyqsvbxr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtzrrrglew.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtirwegvrj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtqhlkwfwu.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtkqufdupo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtudzuobll.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtcvxpohcb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtwebfidjz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtiophcnyu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gttiaebkli.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtvzvxiprp.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgdjgrnxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtmbeqwtjh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtsfvqgoje.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnoezhyiu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtrbpjsuap.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpdzuyppv.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdejyqskw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtdxhylwdf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtupqztanw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnisefnfp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtavocpusp.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtnvvkulsm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmapffvsw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gttpihgwnd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtcdmggspd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtiygagsqf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtcgovnekd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtawbvisbw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwtgnndry.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gttayqtssj.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtuzlfoxls.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtursssqzb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtvzkraytf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtmdykqmjg.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtyhtrrxke.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtptgreeuy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtzewiycvu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtlipzwlbt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtbieifrau.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqwqonvcd.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtcjipyenw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtniaefvlw.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtnnahhgwv.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtqdeghgvi.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtqislkmxn.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtatsfiyhc.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtngibnaqf.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtpozyaczb.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtkoincowj.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtkiwniuec.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtzibfmzjd.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtgmkapgmv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtuhplcljo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtctvljtyk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtxnlmuioe.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtiijeafwt.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtgmyvqlws.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtghtydflt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtetsaksoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmosnbfoc.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtvjqoiflh.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtdkhijnou.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtnwontfrs.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtajrufmmk.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtndxyqoyd.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gtelquejxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gteqgvkidw.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtozmrmmcr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtsqeyggga.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtpnfhafsj.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtppmgfrka.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtceajaace.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtmfjgqchi.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gttmmyfipz.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtxreqolvx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifsrmwov.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtnshgaydm.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gteehyghfy.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtyqvcsofp.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtfbakrden.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtthluvncw.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gttwmcjuvp.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gthdnnuqrr.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtxumtpcfr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtvhgritpg.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtcsnbdzgk.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtcwgtucvn.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gthyribxmz.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaiybitd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtdnjntlom.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbsyjfvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtxkkkzrcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gttmbwmjpj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtygmfquwy.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpukxgore.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtmofjvpck.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtqeuvzdib.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdshmlqo.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtdhrvqclc.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtxjxzcldh.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtmkwjdame.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtxoxmdfui.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtktbbjccf.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtbpzokufi.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtwtkcxmmq.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtxqcwupfe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gthjozlkeg.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtaojtvqhe.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtzfwqnkww.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtoxutbnuh.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gthkeogkjt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtizjulzva.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtieotqsga.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtvijcdpvj.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtsjzqolyl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtqlmwwkor.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdndmepu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtsiruyunr.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gttdkdgmfd.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtiptottbu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpcofqppu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtqoythpju.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtwkvzoxss.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdgqsfxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtkhlggvfs.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtcheccjii.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtcitfqwcy.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtwmcxqjuu.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtvdourgvc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gttsdriyll.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtttdbzqqn.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gttvxqfykn.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtkrekulcr.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtfcxelbsu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtuiugofsa.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtcyfwjurn.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtygzfbkim.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbtemhyrm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtxkcfuoca.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtwxgyuhhg.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtswtxzaow.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gtizkcedil.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtfbctxgad.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrvwmlitr.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxocrpbmk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtmwwnfgoq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtrshfbkmt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gttmymfkyw.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtqbkmdolu.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gttbjehexa.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtpxbmcpjf.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtffhxqecb.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtfgsbxzku.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtsxvcjjos.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtqmzllbkr.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtcfdlsbzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtzihncbdo.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtjusxctvf.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtoctkhjus.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gttrgarxxe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gteleapthq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gtpqlisrxk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtpvtjnusz.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtudiizcft.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqesivbtn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gttufcaime.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtydfbvcbf.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtjspjxszh.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtsefjaqcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtrevgwsii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtoluuzwix.html


<!-- 参考信息 -->