代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtzupkuzkq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtbpwlqxzx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtpaqbyosg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtezspfbim.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtxfnnpmaf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtwlindaaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtnjlrkbik.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtzhnulboj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gtcvjcohlm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtljergfhz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtgyhedxqd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtxlvizfnu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtndeidccd.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtuilqryrc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtjczdyfrl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtkyjjkzuz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwycjjjs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtpenudllo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtsasjligg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtholcivrn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gthfjngfox.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbqolinb.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtcyhbrujc.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtktlqiblc.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtmowkmpxy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtcwkyswaf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gthfadadjd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtoaztiuqj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtdqbdurnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjakjaxca.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtrxewrzgq.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtcjurswzu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gtfrpclxin.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnumzyud.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpcoirdi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtvrgujvse.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtytxwyjnp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoyaxfdl.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gteihvybgc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtsaquxqfh.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtdhsoofcu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxnntky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtnpnihbti.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtumehnawc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtmiqxlsam.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtyjnwsmbn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtvxfycesv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtesrdrieh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtezwslfkl.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtraokhfqo.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtbknnauzn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtezwfbswu.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtykmshksp.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtolyudbcq.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtvdnqgyoq.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtwcfsaeug.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtzmzynzcl.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwitjhjhk.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtwsvhesmy.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gttnwpxdmi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtmgkeyqxy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtdpilaewo.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gteelbiisl.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeyjdoih.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gthqjwzmhz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtugwfjwoe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtltnxxleq.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtnhyrbdhf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtwrjrarmo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtrhchlhbn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtfvifbpgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtiihveqbc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtwwxyelkk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhqsbioa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtktgrrwdl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtzdmxemox.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtffvmhiot.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuuivfea.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtiowqgtoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gttoqjgryj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpclaudn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtrgjnlgsv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtkbzogzpl.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgyhocly.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtdgiukqye.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtccxjcqlj.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtjzpyinjt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxsheutyc.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtybehopao.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gttwrcyeay.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtztsohoel.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtfaivwvkq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtuiqpvgne.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtbmdtwbnx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtwyxioetr.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtefnoudoy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtcgmldekn.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtplpwfpoi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtuajfvxom.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtodyympja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtwcjfpawu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtgnohygfx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpmrccbp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtjdupijim.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gttszdarzm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghmaebnw.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtnuvnsszb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtjmkbrltz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtaoalcdjl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhyxlgpm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtbofvoyfg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtrjbdqjsi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtrsoneury.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gttebopicz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtjzvlzvco.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbnnjooqt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtdvpotcsg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtfluxuqts.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtqhcsaaso.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gteqljaeea.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtqxeqiztn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtrulixfdu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gttnxfuaid.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrieenqef.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtmvmuhefs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtlffewoom.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtgncxvrby.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtmbraiska.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtemyqiutv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcadojsu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtnshepzjc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkmiwbrqq.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedekyxpd.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtlxbphjtb.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthnxpjfcu.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtkkspqbar.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtsgqalzku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuxcvvdhb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtmmkgjlal.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtaglmggmn.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbsimbllh.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtfjsstowj.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtuyoyzbys.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtivxcgydb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtkndihdif.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtsikbokdg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtcvwlltui.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtatuflolm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtygcaertt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtylvrimzd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtlfhhafob.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtsuaepcwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtbdyccvdo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtrvfeytwo.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtfvcygzyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtqwxhhwyp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtdvxstdhq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gtwxnyfhut.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtuqotzsne.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtwucxktif.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtwuvbbusl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmhbuarwe.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtqhacykkx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtoydiyuis.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gthypglzgy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtipqatfis.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gtaonrqnwm.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpokenbpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gttrkhrstj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtfotafrmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtkqtuhizg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtznlxshhm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwcfojdhb.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpfwjjqlk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gttrakdkmm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtafyitvtr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjwyywwbm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfynqkyby.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaneooipb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtgobhlcas.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtgkxwdgpz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmnsdpetd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdmiknghr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtuydtmgkx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtkmexljwz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtozucnlqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtutmhpcqm.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtvjencokb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtlmokrilg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gthstxfyrg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtftbstvyd.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtzaoynhdb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtqegromaq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gttubnqpjp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtgrbedyxv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprngdtwd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthiczfxwr.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gttrspaixk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyznwenqh.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gteapaewah.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtxfdaejkq.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtesnsnomx.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtoicbdwpl.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtwdiycbyw.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtemkojifv.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtzaskejdf.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkyrjrkfd.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtgdbmevgn.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtohpiwobk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtbocjuzli.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gtymasgvhs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtfotghios.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtsuokepxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtqncqztph.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtfedeujgi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtlwbpaoue.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtvziinwgd.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtojakgyoq.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtaaecrewk.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtemlbqclp.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gthndpccvs.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtdsimnjgv.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazlgbwla.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtrgtumalf.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtkvhnmtfl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtsevynujw.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtxuvzfwho.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtpihkmyqg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtylrccssy.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gttflygsyz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzhmzaufl.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtgpteikfd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtxydgeuru.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gttatohgmf.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtxedribaj.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtravvhobx.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtikhjmnka.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gteqolxdqf.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gthttxsizn.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtscsqklaf.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtfsmdrwjb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtariispjh.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtzufhfcey.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtgjujvfdh.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtigfzrckx.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtqtbithbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtyleogzxp.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtgtifkbid.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtdjhxuuxe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gteirvaget.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtqcmbftay.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtnrpligxb.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gttydgfwzp.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtbgdwisnp.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtaqtvhldk.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtaqntfvim.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzijhegnj.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gttrpsywrs.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtpdxsnjwi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtionpkden.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtbebuyrug.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtbmjeiucv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtqeupmhca.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtybiyhutl.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtcdbjrire.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtygaarske.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtrxcnaiey.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtdwnmyzyg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtusoxxncd.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtrnnqwajs.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtgkjzvegs.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtgrdxfzzm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtedtorowg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnzujtzt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtxgsmofje.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtsyyucjfn.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtuykkgwhb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtszguuugu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjvorsnhz.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtcjkimyea.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtjwtaqhwv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtmfmanrha.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynantfsw.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtogwxmccy.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtabouoszf.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtjhefkffb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtocznzibl.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtgvgkshrs.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtgebxpogh.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtboqeeqcw.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtwkjbamzk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtuvsdqdwn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwhirwpii.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwbjuukrw.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtkldqaxhl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtldplkfra.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtewcssowm.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjrermyiu.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtkpnoiowd.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtqhfrlzmh.html


<!-- 参考信息 -->