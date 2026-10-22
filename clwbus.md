代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gt2qzbfhzzl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gt2ktzfnamo.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gt2pxscnbnz.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gt2ctxlekri.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gt2hujxyuxx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2pcuanbdg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2yaicxloh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gt2vbabnovd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2eqpasmqm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2tncinjot.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gt2mmaiuzlm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhmymosy.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gt2necfupld.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gt2asuraono.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnbxxrmr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2cfprmktu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrslwknz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2oektjbsq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbgkgbrf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2tmnuhcvw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2yyeedins.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2llkdpdnd.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2crtilosp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2rbxwpgjd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gt2adtkpldh.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2akmtdywt.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2virbpeae.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2gdzhkziy.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gt2qgfhnqmk.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gt2buwdzkpu.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gt2vapazjkx.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2egpibgzc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2xhrtxudv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2zladjqbq.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2kezjatdv.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixnowdno.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2dypbxubx.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xicpoyop.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gt2dimririp.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2ekkefmyn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gt2ntnpusxe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2vbqjffvl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2gsknatdw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2aqzombun.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2kkcxifqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gt2dokvtkhs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2vqncthtb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2azpltqwb.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2krakqetv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2znqbyapm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2owcivsjd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2prauzkyx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2zhyrjjqq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2qbsszdvm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gt2oyioheic.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2qggobfuw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2yaarhbno.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2bdafsmwj.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gt2twxnoywr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qbaslzet.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gt2uatcpsaj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2ylffivvj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2aopclssj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gt2oxmtdvzk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2qgfcschf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2bermfugf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2wyvdzmdm.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2gfnwyuvc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2dbqnhfke.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2trubcbtg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qywgawlx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2vrxvxlbn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2rjyrkwjo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2omzgzxqc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2ashzwnik.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2blqxkasa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gt2ieitbwhg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gt2tgbwoqlp.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gt2qkhzhfft.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2kyjwvrqz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2gfpxfomk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2yfvqewsu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2erpzqjhm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2wdjudcuu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gt2horrieko.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2gxyrfyyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohweydhw.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gt2drxsxeij.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2ziwzfzuy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2pussgjra.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2eabrnclj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2clavktji.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gt2hnjkjpfz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcgtyoez.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2fhhoqjih.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gt2jkjerton.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhwkjjjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2lslrzwhp.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2nhgcvnyl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2fhaejexi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bmtflrej.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2tmoccunl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2jogxgunj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dtcncuug.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2gphfnqcx.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gt2jfntfzrq.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2vuwdhpta.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2pmkoybss.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hikpxvfj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2weqeonmu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2ppsqpluh.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2zfgioqxp.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vkxtsajz.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2cglzlxiz.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2owympvyu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2xrnnstqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gt2etkfyhfp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbhpapfn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2mpnyrwgp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2hwobrahf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gt2dkbgokqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2xdxuqbsu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gt2ovfvwute.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2ccszmkyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gt2upcrfbuo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2goyatrmd.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2wtxscpfr.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grouqyqm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2naqslwvn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcqacrac.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2yrwjmnxq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2eewtkoix.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2wvmmniju.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2egsppien.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ukxiseon.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2jbkwlatk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2ezcsclbv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ssqteaom.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2luxvlocx.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2qlegvpjv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gt2hvkkplxt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2eezlgbuy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2lzvvijbt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gt2kmfideyj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2rgelaxvz.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kkquvdbg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2zjacetkc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwxxmvlq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2rsaehfrg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2uptrpzpc.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gt2xblcyadd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2twqavybe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2zyetcvgy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2byedqexm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2ribjfexe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2fzlrijvs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2eqokxrzr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2txuvjwae.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2nbdxudae.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2csluwnqq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gt2bveroomy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2ujahpncs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2syxydjty.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2fqbaocnm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2vcuwohdt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gt2hjqffbyj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2wcmnvbee.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldvgxnkd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ymssqsmn.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gt2ksxmobea.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2kvhikppk.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gt2vsxaaqdi.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2thxqsfcj.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2bfwiixvl.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hjxrpbnt.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lnvgjyye.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gt2jcxkmrcf.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2zjzzxiqh.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gt2xeyacpvy.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuacfyzu.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2gpaymlwo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2nbbxsero.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wekogxqo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2rkyyworu.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2yekkjyzq.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2mfvkbbpb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gt2dcmfbixz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2xccprivw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dtcdxqfl.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2wuagtehh.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2kshqrxfw.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2blvaigle.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2bbyvzlsy.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gt2emfhjwbh.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2bdxxmzna.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxmktltd.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2diyibodh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2kfbpazwz.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2uwfkujto.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2ajullfum.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2iclblsyl.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2nvlovonp.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pucfgtie.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2juwkchsx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2nzywdxxi.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqonokzq.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2dcwdputk.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2eqtsiluc.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2ghdmxiat.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2lqiidklt.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2fjtuxjho.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2fqmhlqvu.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2lxhgzdhg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2vzsyjcnz.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2dhygxmhs.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2zxcwxueb.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gt2khpitddc.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gt2ecylkvod.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2ryuklnqy.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ioenmzic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2tvkjdwsl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jhwnkovc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2smsqjyrm.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gt2deidiwpk.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2ylssvyab.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2fxyvqmgr.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2yxwmlnig.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gt2goggevsn.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2fybamxvt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgacylt.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2rboppvlm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2jppjctvi.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2mwlqpliy.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2iqsmyafa.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gt2mvjveddv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gt2qnphipce.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2npxkrxlt.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2wodldpmr.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2zbwlzppb.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2xrnlbhbg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gt2qoitzbkj.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2pubkyreb.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2ziiolbgt.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gt2invcnzae.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gt2kwixwhpc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gt2xsxxdxyx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gt2dnvqqsbn.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2cudtgpzn.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2npdtzevh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gt2rocxlejp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gt2ozuciuah.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2punjndrw.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2bvfrkmnk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gt2netqnqgu.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2sihdtqsv.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2xzkgkuqa.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2bbpfxlmr.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eblsuakz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2slkwrnsz.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2srgrloyi.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gt2pwwyyebc.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2izpmmtso.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryjcakyl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2rwoirhku.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2lqvnpmmy.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2unbaghic.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jfrvyhsw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2xvjskiqa.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjizvfpo.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2fxcqagso.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2nnpgrjbp.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2lakcblhb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2owxcoksx.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2ztispkjk.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2juzyirfe.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2jdzfwedu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2bwersoqt.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2hdwfzxrp.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2ssovxzht.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ibknitgn.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2rljeqify.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2doajdkfg.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeqreobk.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyyneeel.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2mtuayxxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gt2jocpsoxz.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gt2pyjhbuzb.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2rxkyejcs.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2mdjdytff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gt2zxzbrwnd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2zlcbyaeh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2ufsxznjj.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2fscjywkc.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2eunhnmqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2jxlxwzmu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zucjyhog.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2eulxxlms.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gt2izkwfenb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2dfwbfcfa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gt2zjmribqq.html


<!-- 参考信息 -->