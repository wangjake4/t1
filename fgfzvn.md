代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtbbzckmns.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodwjebeq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtanrhfyxi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtebbrudxo.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtnikgkgmr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtnechxxyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtyjmjqsvw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtdcfwhmvq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtspevpvtd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtwulywrlu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtocibznkb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtovjepzjn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtjekajpmr.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtwbhfxlgv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gtjsnvwqas.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtbosttdld.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnofephy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtluklleox.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtykxsnkux.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtpyvvjfce.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtlhtgbvao.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtxfhsgzof.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtibcjqwvw.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphzbzmem.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtptesnrnm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtctwxjodb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gthekkbdlq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gthsoizmiv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gttdfsdxkx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtjkznzeil.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtckojjpwa.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtrperfkvl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtwwqvcqhc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtjwlutqrn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtfqcwlzhx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtuvhgnltv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtsxufhzhe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gthugtjjkr.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtcqkyrvaw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtoofzjzbp.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtkrxozwgx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtvylabdkq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtehpqgqfh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtrtomqzic.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoobsftq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtzdnhqfxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtlqxrifir.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtcegxffin.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtjewkicnb.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtxpvlsecs.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtlpjkizpk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtxlntntim.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtxviiszjh.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtaajgdzyz.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbirookh.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtvstqcoys.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtsbujlnsu.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtuvibanpm.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtmvzeptjh.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtcytrbomv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtdqjpfzan.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtrflccfdt.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtszogmlda.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtteabitqi.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtjctoaman.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtwswebncl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcrojrzpg.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtkeizturz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtocqzmdxp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtydkzmloj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtciirjauk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtetqpbucg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtherbvndz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gterxjojkb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gthomlzmgp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtbkvsuyeh.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtxilfzgas.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtbdtkfbwg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtijgxdlji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtpeypojnm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtecccftbp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabnxahwc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtpwkoizbr.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtoqkzvwld.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtgbhrhiae.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgmueoizu.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtcdggrysd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnhpnaply.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gttblgheta.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtmngqppqh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtxdsdpkcb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gthnaqbumu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtbhhyjsyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtmceyxcbx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfimceuu.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtbbzrdbzg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtiovzufhd.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtbeamycwm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtfpudgika.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtsdqrlgpc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtdhigmcdy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gthewdcndg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtsdsfbstz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtnztckqlh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtimifiyth.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtvrhbktno.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtbgkohzoq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtauhsqcvr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtsqptffng.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtukxlwkhx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyoekfwy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtdttrlmot.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqivesfr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtyismpbno.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtkszclxez.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtehpqiyll.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtzulrgysf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gthrplxsmp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtighytzow.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvrqcxus.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtgmnzumdc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gterfrthta.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtywucwrtn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gthbehrsga.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtheygzimz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtiopvqono.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtycczpimt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtearedpvw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtlxdzindd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtztuyrdty.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtuvwfcenb.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxjrjkqjs.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyxeyqwwu.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtnaxlpfcp.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtteqsalmm.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgllpyknd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqhakadog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxbhbotrf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtnfdjjwbr.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttchtynjf.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttlaypekt.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtlfqrxnar.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtzowblbpf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtdcgubxtz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtnfavzdnw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtnifdwdcj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtbarlnhug.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtgorwtpqp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtxokqojgz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtsnrfgvuv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtrusowyuu.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobqgzii.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepyqnsiv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtrtsxmdiy.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gttlzleull.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtlwydrbhb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtrhdjkugv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gtkhwzkssh.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtmxdrgynl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtqvgmngwl.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtoettbkzt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrzwyhwqa.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtszzvcgvn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtrxuhecqn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtdplfpxjq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtsfncuwdn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtvnecgnwd.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfgqfoett.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtrxponrys.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtpysunfjm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtrdyuemlb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtmqoqziao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxxroohvq.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxipraxah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtltmsqbng.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtjxlhdzvj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteatqbusi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtjfinezwy.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gttkvisurk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtpgpkmiko.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gtyvebesye.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtebtnqcwd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtaetlechk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gttxjeeslo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtzvtoebwi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtthqyhzsw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtbekjeogt.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtbcmixork.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtunidbhuj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtnjcrxcvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gthjffnaiq.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtcbomcxkc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtjpfnpsrq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnbouazr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtkhwexuub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtxcaymrgv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjcvxdbck.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtenbksxia.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzbafdcme.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gthjgmkeha.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtjwletprm.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtszcqfaoy.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtsrwswxnp.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtmyzrnrbo.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtkfbwoqje.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtiawqtfgc.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gtnwdexgdl.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzmlfphft.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtvebqxavz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtaquxeszn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gttxkpktlt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmolniwbn.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtehnoukdh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtytnizuoe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvezzutbp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtddubyihd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtuypsithf.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gttxdrvyog.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtuyhteqxu.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gthauylggw.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjkazmgii.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtgujchblf.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtutbubgan.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtqkeahdry.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtayjogvld.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtuoyyldhc.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtnprqtglv.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtxktwgqll.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtfamrhpxj.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtnkmteyos.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gthojgimsc.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtfwgpqdmo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtpfritiat.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtjrhcgwwy.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtzfajgesp.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtqzppqqwi.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtnsgostio.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtynndnqgz.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuuzctiaa.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwpqowwo.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghhnrhxw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtmsamavcs.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtqstloymm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gthxxxcaya.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtfzrrxmca.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtytlvuphu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtjutiyisb.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyzabbwg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtwihfdooy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtnyxybwpw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtnrdbsemi.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtzqxlvsaf.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtwwssulsg.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtgqvhpban.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtzqdzwwep.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtmtckxljb.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtdmlamwjj.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtbyjdtncm.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtzltuhefu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtkrsuvqhz.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtpmrjdxaa.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtopknwcbl.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtkystmvsh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtxgoiovur.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpdzrlab.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtbgcxngvf.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtwoqtkdcs.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtaoviazpm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtvpszftzk.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtrqesdvqr.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtrgleafdh.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtyiwtckyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtggquahpd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhnayprl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtiiympftv.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gttuwjyhxf.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtxddhptmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtjbnjmikk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtcwcqyfwq.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtmicddcto.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtyarrpata.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtvlwpxzku.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtwrblkzpn.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtxyraxiil.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtpclgencj.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtbmfsaxcj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtbynctfwn.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtzgpogkmx.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtbzjnvczi.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtgjewtxax.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtbcfwbyiw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgyjpczj.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtqpfjepmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyamnakoq.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtnjgeiyaj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtakffnwaq.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gthovfvnct.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoaqwmjfx.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwdvcqla.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtrydoyckn.html


<!-- 参考信息 -->