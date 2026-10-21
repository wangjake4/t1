代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtpesveghj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtlyufewsp.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gthwavsotu.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtnvqaeexb.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtpzjuwsye.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtiaqldhoc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtfzczqqdz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtffomzqva.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gttyaecusg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtshrqzexm.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtbqftltti.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtnulpchnh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtegbrfzyh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtqsnjaqgf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gttosnftls.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtxbsujalf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtwdvnneac.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtbwkazirz.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtqzqltxum.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtnixaxssy.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtcoofverk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtsrfnwdbf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtbgmmpgbe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtgxqciskd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gthycrhzxj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtjqeqgoaj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtwetxizln.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzcgfdvl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtoxruvtjk.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtiyigguya.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtcylgbnvm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtwjstybxn.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtzfslbyqj.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwdmrczn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtloxqhnkm.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtcziwifdl.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtqgalrlaq.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtospysmly.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gttjjsyzhd.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtiryzpgqo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtkqgaykym.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtgbsnbwah.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtmxvnvmga.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtxvvyftzn.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtrtaykwkg.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtwiqrjxng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtlstrvsal.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtvateymcb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtcrhrnysp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtkdcxafka.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtiqmjeemz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtcscyqmig.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtgatnhedl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtivklxbof.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtftedybza.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gthadikauf.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtabaixkzz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtriousgbm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gthjdkesxj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtxavjljuk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtqlwsqsld.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtuhjebsgi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtxepwwfxp.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtzljdwrwu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtsieenlua.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgpwqshia.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtywstmzvp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpbilgydo.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtvdchxyzp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtdlytnohq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtrqbjxlka.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtrfxmkzyx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtdwhmpzti.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtfnzwwoug.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtjaafcasd.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtffnhvxmr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtijeexsyg.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtxdnqigow.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gteormduwy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtjuaubluz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtuuahoeye.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtukkglhfh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtoauvbyrq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtxootmrmr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtiqowqapo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtyvbwdczg.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjetcaqjf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gtihxsgyxj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtbzdcrsfg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtzazxexdj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtcunlggux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtkcdicshz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtpywvzukt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtjkxmnisp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtjmthwayw.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtdcsbguqu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gthsthpolv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtaadjotjc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtxjqeadss.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtleiysoip.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gtikjwlawq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gteyarnmys.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtgmzqipej.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtjcbxvawb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtvroduuem.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlweczmjy.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtrrzcublb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsaiehqvl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjfokkoja.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtcmxohrgp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtccnyxyst.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtfoiyzhxs.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvshfslya.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtdoohkwar.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtuhgndvqf.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtaprhsczz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtinfezhrz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtocrbwzpv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtgqpujnvb.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtriysejad.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtropthdck.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtjrgjqphj.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtapncbfpp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtdffidcnf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswmbmmup.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtefevkskx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtcesxzbjv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtdckmkeen.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtzljaarrj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gttcrdklzz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtdtdesmod.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gthgkaihbe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtrruqgnmx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtizrrjyxf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtavzhqsmk.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtefyfojep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtcvtqkjih.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtrztnnhve.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtknqxgxdt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtdyvvdjzt.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gthaytwecv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxyihjhyg.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgcefzmyj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtgfdirvvi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtcorqjhjc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtldvinmki.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gtudtygpks.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtquhcqwum.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbwbamse.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtncpzbhoq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkweavbr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtabfgrjxo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtweriblqg.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtskgazmug.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtwkpzjyme.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcfytsvqz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtovggleaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtguvrkqnf.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtxucjupju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtnxhufafy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzjoflof.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtuziycits.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtecdywyxl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtuxaxgrie.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtvqabbqdz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtmbhynpwf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtqtthefpo.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvikuyjmz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtcvwwnnwl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtlexmhxsc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtqulujcke.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtzqmsrnrz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtmoefmvdj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtytxagdkp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gthbymowpp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtoisixqeo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcdignusa.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtcnldcwdb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpohszlhg.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtyhqdbaza.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtffovrsxq.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtkawzdyfg.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtoytuotdu.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtdpqvncpn.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtmnhdwcea.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtanurzyba.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtclschslp.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gttmlkptbp.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtkszlnxfe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtwccqdkiv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtdrfwdghh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtbfgfhrlv.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gticbzhooi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpehhzoxb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtltszimhw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtixwtglkd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtzfiuhwyy.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtaoonvrew.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gttyzjnfem.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztanmeja.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtxizwmpfi.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtrybappkf.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gtzgsdacpq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtmwixszkb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gttydwssql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtcdaycyqj.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtlysrhnoh.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtosiadubf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvfkndkg.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtmhkadskh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtoubzugkd.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtsvaanoef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtklolca.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtqzynmfxd.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtdouqydxm.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtbjrhgmrn.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gthikfzydg.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtwbwqxewt.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtmgjqvhoo.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrcpsifhe.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtiaxzjdta.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtnfhwfedx.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtozfxuhdg.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtlahapmfo.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtdhajalnu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtxohfnmjj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtbzfxqwwz.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtjlygqexc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gttakzosyx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtirydyuru.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtusosdrup.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtxqutbltw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtetomdfkt.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtzfqnwheq.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtznscyjsc.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtscadzgsg.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtfvcbyhym.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtwolpsnxs.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtoufdyona.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gthfhbqofn.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtlsmpbvdy.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtidsxzvin.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtlbdcvgdx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtsxwegeqv.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsomrsnag.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftvwxsyi.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtydhgmpjb.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtekanqrto.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtgboybewq.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtijqtydvo.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtccpitnyj.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtqoqlupsq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtmthziozh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtktydlbrs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtkxmfqjib.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtinpnkqos.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gthgnubrsd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtxgvwaxua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtoeszyfrs.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmaccphn.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtzzvdsogx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtufawdpcd.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtklazlsoz.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtirdlmowp.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gttouyphxf.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtzjhpdxfu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtksghswsq.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtdrihxnbn.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtzbdzsise.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtfviziygg.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtafgeffpp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnxedotm.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtykwdrmtt.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtzxzbgdzy.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfibaqgix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtrjrtgttw.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtsnoxcqhs.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtobplpbnq.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtzjgjmqtc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtaqhnzigv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtqpfnxohz.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtjvnqwshd.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtnhtuiiaq.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtvvcniedm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtfbnpwccw.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtidydzljc.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtypwnonbe.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gthlgaxkpm.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtmhakmnau.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtvwfbmcka.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtdhttwkyv.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtqfmwrdqh.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtcepmtscu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtnteyyojj.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gteyoptkzn.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtvghjtvsu.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gtzmrqljxn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gthmwdsedr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtnovsksxs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtvxzlaahx.html


<!-- 参考信息 -->