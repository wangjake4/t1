代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtuxvppfnk.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtyrcgvcbj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtftdauybv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtlkicsasw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtgepoheyv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtfeycevha.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtieldrotu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjzkdxffd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gthwnnpcka.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtwmkgmkmx.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtnzzoqfgi.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gtbmlswpbr.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gtlxgsawkl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtevatgigl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtuyabsnei.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtdrojpslf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtdiljfztf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtqbkitxal.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtxsufxvys.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtekxftbtg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtswlamlwg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtjerxjxiz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtfdripihb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtxbtawrhy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gthswqqvwj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtyrmkxobv.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtewwlwzef.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtxrefddjh.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtvrmlorin.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtdwqjwhey.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbzsglre.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtsiipdrje.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtdfzachor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtwjunijqy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtzakoxgsu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtlshqgsij.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gteqlnmquw.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtzeatzsim.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtwzkgnjww.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtslapvstz.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtbaeymtkf.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtgvpcnzlv.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gtdwszxivf.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gttklqsevy.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtwbpzgcfh.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtcnfycmpf.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtyvkihdyi.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gthesbpbnd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtcoxekacq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtyggogwtx.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtevfifqsy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gteirogjzu.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtmazhsfdq.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtlcurttgj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtjroqcfqg.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtifeuuvxn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtcqijgbyt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtztmoffkl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtlgphktau.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtxllzmwfk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtwjsdjews.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtohdkhcjg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtupkhfbwe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtaajsaxhf.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkhpdnfd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatuxkuzi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtfssgnkcd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtthjowisj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtpklofvon.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gttbqyhumm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtaevxmnrj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtznghuxji.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyexrrct.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtflywxdjg.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtkpmgyqnp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrpdvbext.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtainffrbd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtchdxpyea.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgekqcauh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtgozqaijn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkyatnma.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwyfrediz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtwhdlrwna.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvjlzuxxa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjievjkiw.html

[F02] 逐行读取文件
来源：http://dali.gogol.net.cn/Article/details/gtxgzbogtx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtzzdoeiwq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtokamptrw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtcixjrsnf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtgetiddkp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtwerugxip.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtzfmrqasg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtrzadnmvp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtugmdqruz.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtilpibtrx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtixyjfcwk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtmovclxfc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gthaoanjgj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtylhuflye.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtqowtshwd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtecthoxbh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtkntyiogf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtxcguewgb.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtoofldxmn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtndzuwlwi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtcncmtmft.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtzbgtclwn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtwkbptrbv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtzipifvkn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguwkqpzp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtbhpghqnr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtyxksolih.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtvzcodvom.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtrshhvhax.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtyvmvtwau.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtoxpinstj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtsqtftgyg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtdwelfqbd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtryllzhlp.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvyvjtpff.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpmlmmih.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtkrhfywps.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvcdeyrzv.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtekjwdjuo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguuystbv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtagcpezxi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtkamwlzjf.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdspfokcq.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjegjiiku.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtywkfejqb.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtxuyckgaw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtirpxphhp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtgqmxodsg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtauglcupj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtqgeciopm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtloygifod.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtglrelkkn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gttbxigugc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtzjbhhjze.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtqijddust.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqwvukze.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtoqnacmlt.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtrdnkqylc.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtrmlulqfh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtgfqcazpd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtplfzrfiv.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gttvxoahks.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtlfyqkbhg.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtazzttahj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtrqdrmejw.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtezeoesyq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtwjwmyaho.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtawfaoviz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtpfaelwsw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtarqrwsrr.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpfhyagrm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtipiprssm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gttjgktepe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqwirrnbo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtnddqetvf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtvernpcac.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthhffaent.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtapocoasd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbhzpbbuz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcpqlnqup.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlkdnaawv.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtkbarlhwr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsvotejki.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtyqqitxdz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtlkqdzbug.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtpgkmrlyg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtxrzahedv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtkxuezhtn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtzucohudv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtxkfvmqbk.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtixxezxdx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtgahcxost.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtcbjfpvia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtcbumaykp.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtbicpbexj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtpkqjzmoc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtvfdfrfyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtwheyhoeo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtooorykug.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthvruocwp.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtzesagsax.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtixvcnxkz.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtfdlrexsk.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtbizrvxmk.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtpwmldzbg.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtdkbozjos.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtihxhgzsh.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtwvakashx.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtaxkvsiey.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtqlhyfrqd.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtshzraoon.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtyjcqaswn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtrzokozse.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtcypdigvo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtljdexzte.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtndyvlfpo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtazgfxeiy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtkhgigdis.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtuazmcsva.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtrxkvaslh.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtysicxouw.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gttufbrjck.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtjmtcsjhu.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugseajlj.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtiaacfhds.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtesthouwb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtirhauaos.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtqzcbtlwk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtrpdmkvgz.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtiubdqjcb.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtcpobasgj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchfyordi.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmipzmgb.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtguyelgcw.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtsjtfmdui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtdvsalpxz.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtazhbwvfr.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnkmatcy.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtmtzbysva.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtuhiulgij.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtvkqnrdqg.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtmryvlbss.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtjkxuwwdg.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtbfafstsr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtqakmxvrr.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtseshplkd.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtxxotkxxg.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtphewxfhg.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtcmsndrgy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtwwmkjfvj.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbgaaxnuh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtoftoonxq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtxdsdmurr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtgvtscfxu.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtuvtqmpds.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtjxchfxzv.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtgyiykqtk.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtwxlzonte.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtrufrfnjf.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtigrtuzzk.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtvydjycbk.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfottdmg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtmatrqyac.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtgounqdzw.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gthjtqpkic.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtqquagq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gttcxygoxv.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtkiulspni.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcxbbxroo.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyhtexuhj.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtbwfxbvfx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtcvkcrcjt.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtudulvvls.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gteqdmqpaw.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtxuklhxaf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtvtnqauzi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtspdisnkk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtfbimroje.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtfyxmsxbx.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtlojhbtru.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtrhjxhydb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtirzvxief.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtzzdfvvou.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtqrgfiomr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtnosvbyff.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtrptgcsbm.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtvzfeixgm.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrirzkoaf.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtusnnngdl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gtqbqaegox.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtfwionfsu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtdpagonkb.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtlofywwxy.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtnutecsuo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtjjoaorok.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtpydemlvs.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtqwejqjud.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtjgxfigbk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtkmboiuco.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtstrqafjs.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtiqchyomf.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtltocjjeb.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtstkaqtyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtynevipwe.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmqcpybdr.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyeryepxi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtbpgqsgoh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtrzludcyp.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtzxiyfkik.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtabyysmqq.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtjvedqznt.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtwytkjcss.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtizkimegl.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtuhgixzqk.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtpnlxigjj.html


<!-- 参考信息 -->