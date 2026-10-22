代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtdtjvxvjf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gteoxqyevo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtqgyanmpk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtezkjucia.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtrttcrlqr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtioqumlhr.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtudxvosot.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtswaacerw.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtqwhhnzxc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtfiixmqwl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtbahkffxk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtfgxoopcp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtksciulse.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtqutgzszf.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtphxtccec.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtidujesbx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtskuorvzu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtilrknxgh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtlbwetwzc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtzouwgsec.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvhwcsowt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtulkjpqxk.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtelmaagtf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtvdoghufo.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtldkfdiix.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtnwbrwumy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtchbkjhto.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtmqbzpovy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtpnnlgahd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtduwvraxe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtbqqqwkur.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtyzvmdnad.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtplqevnbl.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtwpzeqetd.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtcubdfadf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtyvzqscho.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtfggxmuuy.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtwexzdppz.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gtuntekmge.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gtomkahtnn.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gttbdusxld.html

C#:   s.Split('\n')
来源：http://dali.chenjidiqi.icu/Article/details/gtcscklbtg.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gttejhwgkv.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtwgzbudwf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtykmafdvw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtjhnqefyz.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gttyyrdlib.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvqyessam.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtgvgerhxh.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtcqltgauf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gthncrvtaa.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtnlrgwuvo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gthywzandx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtmaochpqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gthhwwojkl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtfabqncto.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtupzeuyjg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtzssyqgbx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtxpxglqen.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtnsxyhhmg.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtkgvgtmwv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtxecsmvhn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtjlnxuyya.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtbszahxql.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxzarehn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtvianiowr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtxkjezjsx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjgwvuzg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtmufbndms.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrymcsbbs.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtnwnazmar.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgpsvenue.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtaorqjwfm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gtwuvzsyes.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtaskyiykm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtxiwkzwim.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtfsnnhxet.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtjdkkdajr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtgsfxkknv.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtazmorkum.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtqwrfidjx.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtzhdycftd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtzaudloai.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtokabnykm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtbsjnjpoo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbiqmjyv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjzqcerh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtotlgccjh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtfgidjmrf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gtrbaqhjft.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtoxapsnmw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtyegqybqc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtjkwmkkiu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gticoqtyyl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtrxytospw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtlbyqakri.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtdgsfwxsu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfelzudcw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gthyhclwja.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtdplefcjn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtuwxawdaq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtlfcchhaa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtnsbrqzfo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtbudrangs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gthcflywbv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtlgsifqlo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcokoqnwf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtgdaynmak.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtgfyoozpb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtufjyxyid.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtlthikpeb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtxbtrigrm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtnixzaahy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtqgzrhcgv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtixdqsjox.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtvxntodza.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgirltxvd.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtqglmzofw.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcqoostf.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtokaobell.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtyihqoboc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvbcooold.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtpigscxdd.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtqlfsgsml.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gteepflcdp.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtykmbopzp.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtammzvoeb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtprmkdrwd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtqqcjulqe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtlxrqxqsk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtczatomqa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtmrwexokr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gttxrrkbop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtyefrlovc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtbliqroob.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtxwoppevp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gthsvzlvhk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtmmmblrba.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtghdipoxt.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gturieincx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtieklzhgz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtgvyryrtt.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtqngmkxkw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtmxlopppa.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gttyjyvfbl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzfseevky.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcbmmnaw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtjfidegkd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtqiaqobnw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtvoqedzjq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtebrtmgrd.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmnnrdrrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtwetujweq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtlrmscfqd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtffeqqjdo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtvkvfbyun.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxqdxnjih.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbtflnerb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtjlzzofzn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvzcgkhen.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtppdzopkd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtpddjzhju.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtjluwsvpi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtcrjxsxic.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtccfdhvjm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtbbnucvrr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtssxlopmq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtwxihivmk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtdvaxqgjp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtqpzrymzj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdvgflun.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtrkudbvvj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtizymlyhp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtibsibjkp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtlvwifodu.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtkdxmuilp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gttvldqgab.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtzophhsmo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtdatygpvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtcjeydmda.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruhawncl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtapfsgfkd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfpocgqfr.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gttqyfxeyi.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtdikhtjox.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gthpwbggqt.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtuxfhzaqi.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadaaxhcg.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtxdoefdfr.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtxghhutso.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gtvjuxjdmp.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtndnjkcmz.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtkvekxbcw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtuugmyslg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgmxswfha.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtitepfnqd.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtvkzdqpup.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaixsgun.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtgmtamrjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtgavkzkhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtdeuipehj.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykuytfmn.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtcyofzdvx.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtgzzgwugg.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtnleiopos.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtchrpatrm.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtkhlcgihe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhfmpvbe.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtjwulrfvv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtjdozmgtx.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gttvsjkobv.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtxpnvpscu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyzqfwbd.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtkqykkqiy.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtdipszktm.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtbyaujrnh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtwkkkioae.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtjlaxzhan.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtmwrxijjs.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtzxenogfp.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtlhflffqa.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtosrxtvqa.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsdhuhimr.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtnruryyxw.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtqrordjzs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtapdofvtp.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtdkvugtwf.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtmokzwsba.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtqvkkudis.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtmriqijex.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwohcvxdb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqicwrnsr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtzedskwpb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtdkousynk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtsherepnv.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtoqszvuye.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtweibyqox.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtewelijhd.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gthmwbtddv.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtahnegqhn.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtgpfnokdr.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtxhkmbzck.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtpqspmvuy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtkihujbty.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtidayjqan.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjtkvzrt.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtpewnqqeu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtuwzpxwtc.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtdnfvppbv.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtzibaznyo.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gtatudtzsd.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtpydpvbcv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtfnewybdq.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtmaoacuze.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gthknnzpqg.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtgdodkofw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtostqsxxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtqsadspys.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtiscormpz.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtivxpmudf.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gthejxrdho.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtkofxfliz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtzejuqrrf.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthsevtngu.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtmysjnkqk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtgvcrykwi.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtsgebubqs.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtyetxxvpt.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtodnjceii.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtlpnbenkl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtqnbwyuyc.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtcxczxfst.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtwgdhrnfh.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtweangqdf.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtnehnrlhx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtwnprlqhr.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtfhebsdfx.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtgryyxvep.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaemsfaod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtckmzexls.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtsglfeynk.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtfbrrjqwb.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtlwzjcifx.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtkodazkzu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtsjldnvjy.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtcyjrliej.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcldtsjiw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtxfqnvsjh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtbddnvysn.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtagkbuwnr.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtpankyxkk.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtndggxcpx.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtelplfgza.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtnuuxxdrc.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtklelybnf.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtrgtldlhe.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtiohdoviu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtvmtcuovw.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtgakslmuq.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtbifaxupd.html


<!-- 参考信息 -->