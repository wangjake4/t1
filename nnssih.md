代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtkgvfghud.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtxmvsykir.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtwbfkxwxk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtnaylztzc.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtmlghcnzh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtnsltstvv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gttjrxmawb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtmeikkvhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtfuvewnpn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtzjlpjnyf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtcplblphc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtwfhzhlhu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtnprutqey.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtzrsjrbmc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtsghaegjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtlbxjxvmj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtwgrmsxqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtkvljjvia.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gticmpvefz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtmxhatdfv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtppmlmcwe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtmvuvzobx.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtovadbuel.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtzdqlnytb.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtpumabvee.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtxvjbobag.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzobcawvw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtskfiogsi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtsyxbxeqj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtlydhsoyl.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtcmpaxhad.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gtbkqgdaeq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtgkdxveee.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtypxoodun.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtszqtrgrf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtzfiqjtzs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtuwduszsz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvgkquqz.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtyeqrxrqp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gttaulswfo.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvoyjbt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtrbwayrcj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gthqcfiozk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtnmkfcsmn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtlmumfoww.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtpcauohvw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtwwolhflb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtpmnejrgw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gthkgsrasq.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtaxwbbqjw.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtadsbsjmj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvrrbbgmy.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtkjmicjek.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtxwrlwklz.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtxcwqcsad.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtljfkxqoj.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gthmkskbck.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gtijtotovh.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvwimiil.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gteeptesda.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtrjlncqmn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtlwnpexkz.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtgfczqvtp.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtttuclxsx.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtugnrevnc.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtouhcktdf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtxbtndehb.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteujiwdur.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtlqcizvea.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gttysugrfv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gttsjxgtmi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtiqcfxztg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtwpanmkxz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtbdygdmpe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtvkungnxb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gteyuhvebn.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtmjuhjkpv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtigkxpxxp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtysjmowfl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtrrhrbgtq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewkxllda.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtyvnnktvn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gtaesmzslo.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtefzppsno.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtbsaarrje.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqnymzbua.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtcohjfgjd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxwefovzj.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtlvlmosfp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtxzdejvdj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtbkkhwejf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtoqbpjrtw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtdapjznfl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtezwkmtym.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtwvbsejld.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtrflnocxx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtzqhwwvww.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtjelhduho.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gttnmxomgn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtzibjyvkz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtuwrowdhi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtljctejqg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtwtzsxuxd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtbmkiufmz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtxzcvmoxm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtkhijzsgx.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbrzudil.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtfiztwrpj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gteysyalup.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtuzxvupxn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtzwyqetaj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtoicbgkxm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtfdixzphf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtxvgvviec.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtfwsiqnsn.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtedttkwtg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmnovmas.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtuaiakzcn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtungmbkkp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtplcxarbs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtawdhgygr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtdjfilvis.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtcundkkey.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtvwohooap.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtzxlwxseh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtyzdipzsq.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtgullwsat.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtyixihuih.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttqkxxose.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtybtugwzl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtpttacrmj.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtraumjecm.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzdmaxcwg.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfjhyzqw.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpgjpixrl.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtuwkwprcz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmzsdqcso.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtndijpbsj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gthfmevonn.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmxrwapnx.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtowsxsfjv.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgoiivycu.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtfrwwdxyf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtimtxiwyv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvimmdrwa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtuvzszvrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gteuqcasvf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtxagdmmds.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtwamzblma.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtdqumejgb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gthnmzikvy.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtznsvengc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtcfvzyaxu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtdclciazv.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtjrfvmcbp.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtbeqvqwmn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtlwhdcdni.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gttxnkbnyu.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtmebcinug.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtgmenpzns.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtlmfzkcec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtuygoevws.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtgvvhtxkg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtquamvyhy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtbbyelbon.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtzavylnbf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtixhliipg.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtumwjtdow.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gthxmrphpr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtetkxsnbn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtiraqpwix.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtbiwohoag.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtjmjcbacl.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrnrijapo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gthxadpqxm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuszqhutm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gteykjgcmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtndbzttpy.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtiuubihpw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtckxlykui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtwgwfkhdt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzeijdhqe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtidlztdtd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtxgnzxtpw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtctvufiwz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxamcsan.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtgndpfbve.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtyyrighcl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtrfyrlmpp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtpqxdlrfw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtdnfjtbjg.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtmaegxzxm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gttgduplmz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gttcgsihpx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtrwluhzty.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidodmoxm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwbdwxexe.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtxncnybff.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgdksqakp.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmhimlkx.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtxzpdybmh.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfakmdhnm.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtzbdcjglr.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtdfcymfra.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtjarpljoh.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtbarwtelt.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtmqthdncy.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtcyktnxgm.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtfplhersg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtzgaricul.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtzwsvwcjw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtozqyecfs.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgevzudmq.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtoqxztmlz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtqznvikji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtofslsaxc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gtbaunxgji.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtlnanfdnj.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtvdocqmwo.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtprticnif.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtbrwqujeu.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtduqrhwvj.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtvuoohrrt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtopdpfzdh.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtotuvslua.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtsgypkqaa.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecrgzizk.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtqxhgyjeo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtcxasdvyu.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtvkpvelqj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gticmlduxq.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtpmxcbuhq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtqtssoghi.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtldldzoni.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtovrbbjev.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtykzggqrp.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtyeykuokb.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtlyhygwbq.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtwjemitnq.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtulehoidk.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtkjjdwyhy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtsxbvywzc.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtidwltbiu.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtcadnzzsd.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtxxyhuhni.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtqedrrjqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtjvjphyxs.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrmhmvndf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtkaqckhgn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtatorddic.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtrcnqbzhb.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvvofzly.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtmgenxogg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtojlnuzgl.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtmxumnqsj.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtrfwriypo.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtphcahuwh.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtltfpvrky.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtdldjssqs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtyxlpnvqz.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtgkjovgep.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtttrorfhj.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtjbgmkbdf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtiqibpxfl.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtsahmeobk.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtzaejvjbk.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzquwpbkh.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtngtywwsv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtckinsbrk.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtoxbktqsd.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxngqwsn.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtustxlkem.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtdzzeizio.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtexzsrvks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtdkwjpeqo.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gteojgalcq.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtdpdobslp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtqelgnfsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtevjmimtb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtihjlgctm.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtnaufbvpl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtnduqmeap.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtgqmnrrvz.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtnzzipthy.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtxaeayiub.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbfwwdql.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtvfmxodlc.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcibifiky.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gththxdfba.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtbjfgbpob.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtiddypoxa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtbpgtrxxk.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfvxxpzym.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtbeaondkc.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtkmushfvl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtznzjextc.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtsblbvvju.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtqpnkitda.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtaybrwsab.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtpnotdeqn.html


<!-- 参考信息 -->