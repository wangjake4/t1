代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtxvcvqgns.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtlyheczhp.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtxxytfimo.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtkvtaxuwt.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtnvoxllyn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtwdeuooss.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtrcizohwl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtiywvbnkr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtykdadiyz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gtpxfnvofm.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gttuqmmlqh.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtepyzprms.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtvaixzrrg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtjwvqjbab.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtltifkzar.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtpeewnksf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeujwxqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtgdwticii.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtdzgglnwf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtmulqavdk.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtwminsifm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gtawbttnqx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtjtwdmeqp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtupzowcxf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtivqtcdrl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtjnafnwfc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gthhdftlcp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtxnssslgy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtlgkntiev.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtizyprjcm.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtgemqpaaa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gthijacona.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtrbgcxclh.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gthyjnzxww.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gteijeunhg.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtdognfpro.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtnqmbeguv.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtqopdmgqs.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gthxuwvdon.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtesvkmfjd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtxgvydenv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtlvvjtkqc.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtderfcgtz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtoohmhyzt.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtdcdekcfn.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtlnxslice.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gthleyehvz.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtquuyyqyc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtpktwzzmj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtnaxiicpe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtfxyqiusn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtpugovwdz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtsutdamoi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtplfieucj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtyjlqryqc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gthxapjlyh.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtzsamfg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtvrpyqacc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtcrccfydi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtytjhwllu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtgjilykhl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtiombczua.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtcglctmkf.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtitzximnb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtanyqgbym.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiyvpzmvo.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtccgoexoy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwvwdamy.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtbouuecrs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gteimtfpdq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtmkvmaokb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtvilszhmd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtwghlhabx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gttktzjtng.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtcmpwgbmo.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtxeeothkj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtuloslahj.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtaeuxhimq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtbfkyqpex.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtltapmljt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gteywmwbqv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtujpxcjuh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftjfjnau.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gtjqphdlqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtnzzrkpwn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtklmamlrx.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtaxqczwxo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtxfdxschb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtjwftqivq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gthasruqgy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtfoixqqnr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtmtgvtgei.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcdmvram.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtvhbrsatw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gttnlhrazj.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtnmoqvzfq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtdsdxffqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtnplnelcq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtaalvtpfn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtkmbasnct.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtupaheemb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtamiakiwc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtitpdzpkb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtmoptfvud.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtofecovyu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtmdgqthrn.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtzmkqcbsf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdfzfgfiu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttepcykcy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtavyohbnd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gttehjreyr.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfzdvpqya.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtltsrdtzv.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gttnuzimug.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtporirfcd.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmmxxakci.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgbjbxeit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkguqrlde.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtyazdhbgr.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjxtvlgur.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtwegbqmvb.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtrehibkat.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gtztsvfdcq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtqvlqqylz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtjvoehqxb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtrtojnspd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtmxkyyavw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtvjkfuupm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtimpwnqht.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtpujhsdly.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gtvgecybwz.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtfmjniozy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtblbjuzhs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtzgsjzszb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtpdempjod.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtukmcuqjn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtkiqipwem.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtsksenfwy.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtsuhndhfx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtqommhuon.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtxoumvsrq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdokpwvjb.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtgnruhcdd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtvinodljq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtngevqyii.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtthkjahbo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtvsjvmkpa.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtiptvukpg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gtaeforhqi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtlgshllph.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtenpswdft.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtkdzjimky.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzgvkbklm.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtceadqgun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtttdfwojx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdfjjohoj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtaicvdcei.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwpgirxeq.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtpohkyslf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtxbpgkrnm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtjcofelbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtonehbdxi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtyybotfzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtlitgylff.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtzertcvrd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtiivsmttw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtorhdqthu.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtovyjadwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtoieumlzp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtwmdutbub.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtfrgqgnxi.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtqhvadfsk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtygfkcrms.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtokiliwng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtzufcznqy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtbnrsovgf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtiimcciwc.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtwjzfpmuj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjbtyfumr.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtjlnihtxa.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtpvyzhagp.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtvwhoynaf.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtshsgnkmg.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtvdicbhsn.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtdxarhhsq.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzgxrfvp.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtjzmeuovp.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqxpzgho.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtwnuwfmpj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtvlqotvcc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtesbpfjqv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtbfyflxbi.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtawlhtvyk.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtnctoacnz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtukmqfqhp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtbiuhphbe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtavthqdxy.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtpbetsgyf.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtargirryv.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtgfmehoer.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtcxhqzziy.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gtevmvdnrg.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtiiyopqgb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtfwjaqbop.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtmxfocndk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtthlcaupf.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gttfelvgkl.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtzrrsilqj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gthfzbjcii.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkxiznbqr.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gthkgbtilm.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtwxwcmadk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtdznvoiya.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtrbgveqwj.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtugabprxi.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtrnkfyrqj.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtlqcedvrp.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtelfekdro.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtbsdubxym.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gthbwjpjxc.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcwutkuqs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtcvierlks.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtskvjgfdv.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtvxssyyrh.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gteuzgjhff.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtspcgsgku.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtdnilsdsn.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnvfxfvc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtswweqswo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtkukbcqnf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtpsleoehp.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtnntghlix.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gttpmefdfn.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtwmqcbjfr.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtcpsczrvo.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtpicxheji.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtgkazadru.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtxfftywvd.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gteiozgjco.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtjgupzvku.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtewlqogyo.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtzfklurvl.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtwiksyaas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gthwykpgkw.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gthovemjzj.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtjeexrpla.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteasyhqxt.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtijeynkhc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtrelibxly.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjjyropb.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtdglxzmtw.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtvddoxzkt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtnkxmnlfs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtwasrevyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtcfflsmwv.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtunvzluum.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtijppnsxl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtazdzctcy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gthefyomew.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsmvtpso.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gttjpzbset.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbixzdmd.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gthybjisal.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtknhczzlq.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtmndijvas.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtmthgltgb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtnnqgbpel.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtgnlyqhke.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtvevapebg.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtjgobnjzn.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtzftjqclz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtnfvxhqfw.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtaxftbbsx.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtmudiyruo.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gthapfgxfu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtivxarqyf.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtkkfrpqmo.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlalpmhlw.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtjgletwal.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtroyxpsnv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtwxucvmzw.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gttamjyviw.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtbzbcekfp.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtgdjhynqq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtejkpbjqq.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtwzswelcf.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtwvdjqggk.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtjngmogpv.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtzejeucfq.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtmufspxhq.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtkfryktgr.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gturwkqduf.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtdhkvktdn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtothblmka.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtjadgfzqv.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtfxdjxcwx.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtzhfgofqo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtwjazcmlc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gthnrxalyq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtxdaodtmm.html


<!-- 参考信息 -->