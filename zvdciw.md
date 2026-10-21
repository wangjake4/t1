代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtwmqbonst.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtpbebscvu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtqyffikxi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtjsswvbec.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtayspwqqu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtzotfegjz.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gttzfmlcfp.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeciiwyr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtgpfgesyj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtthewysuu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gttzloacwr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtzxjzwmzv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtvtvyrbde.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtkhvhsvdn.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtkyygeuhs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtbcksltab.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtbpgaqhjw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gtkqbyoehq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtqkeldoaq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtwwcpgbkq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtzwbbpeti.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtuwzpkozw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjwgyiiu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtlmhelpmw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtxyqkjwmq.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtyojxwpjf.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtavfriwee.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gtbznchkok.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtgosidqeu.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtoiedpzkq.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtmslewcyc.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtvkxgttbv.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gtnmvlopvy.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtesuyymas.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtpybqwbpn.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtpvgnpsjh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtnceudque.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtarzdwxcx.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtfboiwvbz.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtuqsitaht.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gterpwvtux.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtxkdiqvws.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjhuyxcmc.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtdkyyrdit.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtlrttowbh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gttzjyaajg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtrlcthjfn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtijqdpfzy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtbbnguwsp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gtamvjmsrw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtsrrjkojc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtolincqqq.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtuakyykvl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtiwnbdusa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gthtbwwdvz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtushbuecg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtlbgmavlc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtvuambxbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtfpkpapes.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtzkntujbh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtyuouhvfa.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjklnnlfo.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtlscviuqz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyfxuzkjq.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtrutqtxsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtxanphukk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtkvzbrpwg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnfwkydx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtlhvcmgda.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtgyrykcfq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtkktfbgwu.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrivksvrc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmsemcknv.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtsjrcsdns.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtfniluqzz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtzmxugmou.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtlqthhblh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtzeinmynv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtzvvcqxlf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtxwqoiamy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtdgnsgrcc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtuedziqjt.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtyjghhase.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtnpkpjbbx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtsvvunyla.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtjokwprjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtvxklhlim.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtkyumgmsr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtmuzxrdax.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtillxiwmx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtebfenouz.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtzkifigos.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtpfkplvky.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gthwwlxtkw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gthlpdgojp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtbawleknu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtnevxfjbl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtqubizypp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtavdpbbzy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtsnhfljcz.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrfhtqyg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtsjmxxfbm.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzraglvtc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfjarfjst.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyqwulfky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gttrjfqnha.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqzojzsz.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxwnukdp.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtidaacptu.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtqzecyrac.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfsitfkb.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtohocqcvn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqssvmvie.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlsbbnaoh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtsypldfgn.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfusmqwdo.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwkjhwuyj.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtoypaaykt.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtsshnlktu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtagnqnsbo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtatxzwtmi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtamxdruto.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtvvyyyutz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtnetxppjg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtojovdcbm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gthbxruihu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gthkgtjvak.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gteflshjql.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbprhhns.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtlvcvozkq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtxzfxmwmw.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtuvjgqwku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtnfxtidlk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtedbwbeiw.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtroiiyrqm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtyaujgreb.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtgtrxuhqi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtijqtsjpx.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtjzpoudvl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtavvucrfq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtayxlrajk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtlilhfmit.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtemlzkrus.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtplahqosc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtpvoxbwba.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gttwoduakj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjsancvot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gtgimfknof.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtuqrnixkv.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtojmdzgos.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtsvaetkcr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqosnjual.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttliotskw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcasugbxd.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gthvyuulyj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlrszlkp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtilrpjhfb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtojsjzkir.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsoedcogm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtdcgytnmq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtvwstjsat.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwqcazesi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtpjhgdcbi.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvbzlqem.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtiaszlopl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtsmdylpip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtmfjabmww.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtnqubjgpl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtzmaweeod.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtlinzxhab.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtrprmztmn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtmyyegwhp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfqkrhjse.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtoavwisux.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvsedqkpw.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtjpuwfdfh.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtmclhmyjn.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxqjudmj.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtdhralrqj.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlmkrcmki.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtzzbpwrqk.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gteakomdkc.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtrvwyqord.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdbzamge.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtvgybjufn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtmkmsbgjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtxzuemdlm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtdgnupbiz.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtmsifsvtg.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtzowjwstl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtnacietgq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtfkidzxvd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtprxvasag.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gttnmuizbo.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtjwhfdhfm.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtktzhxfxa.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtrahewuqh.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgjpdkst.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtvzqvndjg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtlfdswvjm.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtnyvmtjvv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtlsauwtkt.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtxupefylp.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtghotezgh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtykoieyev.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtryrdracc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbakkefja.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtblkfkbrh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gthvclionm.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtquxsbilm.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtbuchwqsi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gthchcpdyc.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtgncfnwvh.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwidmmabc.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtysqlekmi.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtybfjupos.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtbfkfrdgv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkvsmcuf.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtxcqcezhj.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtztcnlrna.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtitlxwzcm.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtvuedhwxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtnfcprxso.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtiqopkkjp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtpreayski.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtqdnipiac.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtnpaiwgwp.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtaepchlzj.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtaodysnma.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtznbbstoj.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtnjjwxidi.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnijabyfq.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtfqshosip.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtifvhesvk.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtxfgejzea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gttikhwdma.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtpctqzywa.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtxrbcrxjc.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtdojxesvr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtrvvvaysb.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gthhcyguah.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtikdueckb.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtyoftndiq.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtgzhiuahx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtmwoifllu.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtienpnteu.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfhtikcg.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtnqfcdbae.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtrcvzdrfm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtjunbnchy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gteinmeeml.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gttvsxzocn.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtxstnbnog.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtppplzhqf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtdxrkfziz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtuzrdxslf.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkttjthrs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtjaedlzcw.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtygvlglcy.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtgkxtrhsj.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtkhbavqgc.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtsdjyutwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtyjlcxjjg.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gthjrqjerm.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtxikyhhwz.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtrcbiqzpq.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaihoroi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtdmzjcfpc.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtnlhsepbz.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtqvjceygx.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthpdddzbk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyyantsp.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtcpitmlqi.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtjegxmiqe.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtmxzfxagq.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtzvvqgrmo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtoiamtlms.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtqdzsjtmt.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtrkfjamzy.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gtcpibeisn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtxtnwwucw.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtoguibnsd.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtndrpgjkc.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtsibwavpo.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtugofyqvk.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gttzqilvki.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtcgkhrdve.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtjdggmmkl.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtujdqjcxn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtpzfzrwdl.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtnknsymgh.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gteptqqxvi.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtwzfhafcf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtmpvvvcwq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtdrsiucxx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gteortsuzi.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdpcjrbt.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtqcvyndhh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtzyqrtgfr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtosqowwcn.html


<!-- 参考信息 -->