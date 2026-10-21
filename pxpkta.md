代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtzsxsgebh.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtwjkpryid.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtawgabffl.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtoafooiwi.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtmxstujht.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjfjmtqvn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtgiyhybjy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtvmvulyoz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtwveziuqx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtonumwndr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtszptqxpk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtfhjjfgev.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtjjjqtkft.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtgjsivxqh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtoonaovvn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtuznyldwu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtzlllsird.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtackyisfx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtwofhummn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtlthazzfn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtnquvkjlh.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtthxwonhs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtrdrgsqib.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtmgbbliek.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtmwhynxmc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtdidefsyj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtigyppxmw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtjcodaleo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtagerfbcj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgasbkcy.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtbghclqju.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gthtdcibkz.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtskaidywp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtdgwjedog.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtshtduwso.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtqkszpjwr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtxxaifach.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtedlmehdm.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gttpdpesre.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gttwqdnkxw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.svipenyu.cn/Article/details/gtuzqfcgeu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtxygxblsx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtxqcwsyfq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtfkdydnin.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtxrjxoieu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtlpyczgsa.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtjxdqaghc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtivbpwthe.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtwoghvhzj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gtutkxrjsf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtqecraajw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtzoibdbvu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtoascvuir.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkvyewbn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtrjqmubya.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gttiflsizq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtbulnnxza.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtnfdzjhpu.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlohnnxhc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtljtkvivj.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtetarfynp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtunevphbe.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtskiunxee.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtexjcxeaz.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtqeplngjx.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtbttygnpt.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtgkvenpjc.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtqedruumy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtciklonvp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtndqnjsti.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtolgndsde.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvbymawg.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtjooebybu.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtxwspkcdy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtfzumovmn.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtwdaxcrbn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtgmwrpxns.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtjcspwfbp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtuqoshrbn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gthhlrkaze.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtxrqraght.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gthbwcpjfv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtgrgelkko.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqnobges.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtklfvpzdf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gtszwqtzst.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtnyuiajbs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtnhlmffua.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufkfaypz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gttpiqpcab.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtlxghqwkb.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtolthzduh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtvocpwrym.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgsimevck.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtosgblulo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebmelman.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtklqerbgk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtylnllygt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgvyoqify.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtirqxnpyw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtipfoaokh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtqrnegcem.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtxlfwiwrm.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtfawuxgtn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtzjrqawes.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtyvscubwt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtqvwfxarh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtmvzomcoo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtmzqfnzyp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gttoulntll.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtfdhqziwl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtahpdsmgk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtjyfzfnch.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtdqznwhjh.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtqyewdxcs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtngszosrp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtcchutjms.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gthbjrwnwq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gttbutsxoy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtukhwdhlj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtljvyfdyt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gteynzpceq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtfjihfiyh.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtfmsuvobi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwhwaiyc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtizzayerj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtwmbrfgkl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtnzkrexkq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtnvxzchyk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtwjuqlfby.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtqotpljzj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtjzexylez.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtnhbmzlbk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtsvsyyxdf.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtlzrazqth.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjmbyelpx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtjonzggjx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtzwvnwbrf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtujgkaapx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtmmuhjvsg.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtuvikgymu.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtvrvpvvfx.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrvxsbmpf.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtdpdjiyta.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtaobopqzq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkjeirxwn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtvazzwgpv.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtdpmbwdgz.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtoaqjxgln.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtmtyiaojo.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtytwsqpot.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtxjevppjy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxmsxbqr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtqugevphj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtnohnadku.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtmyleuunb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtqhhyomae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtiuemenmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtimwckguz.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gttrfdprkl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtjjdwjmgq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtaggzwsfp.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtoomqectf.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtxfvpkqtl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtrqqpwjas.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtxuuhzepe.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtgznwdzhs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtcnndsnax.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtpksmdswb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtntvdealz.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlzxxzgwg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gthikedods.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtnkewaxse.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtjuilmvwj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gthqlrknmw.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvulbnkzk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gttapcblix.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gthcyyfsrv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwvntvcc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtrhvinjgc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtztytoymy.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtydzcqkwg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtiwyymegj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtsozbytac.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtghiampbs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyjswuaei.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtsdihoaqq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtltxzlknu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzaollfrb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtpisntgjs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfiiwjflo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtiphttcmq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtkaolnefa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmawcfblu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvjojsuv.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtmtkdoyqd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gttsrvdnrg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtlpzoznno.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtamlohkft.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gttqffcmoa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtxmsrkavw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gthkccwkmk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtwgwyxuvj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtllvkbylo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthwyfwfvf.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtxnpussdp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteobtpldc.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtlgobxkxa.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtxzojaquo.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtqnrkuqwc.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwlafbbb.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtiktveorj.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtaykjyeyt.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtzbgzrkrm.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtvtbznewu.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtyzfvjfld.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gthlnqjtzu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtigaakdrm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtsnbrzxmj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtsibnljnw.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtckobykdh.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzwalfqvh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtviibsukn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtvacgsibx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtwfcqgvuv.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqydzrzd.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtpqsasumg.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtnqsptmxj.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtrknoclys.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtpfcfofss.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtsduwspjv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtepdfgtli.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtchtqndme.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gttupqeosb.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gttcusxiuc.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtkwkkhtez.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtdvqzcvsm.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtmasbqchj.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gttxdcvjzv.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjfhxkst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtawlejtqi.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtjkzbfvif.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtfgcslfxg.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtkzbcmjwf.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtxutydztl.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtcofiksjx.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtlhhdkgbn.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtrkbziiac.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtkpabfdoq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtznqfjpef.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtxrrbdmbn.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtaaqtlnrx.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtdzgdiskr.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtzbrwbgfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtcmdwzjls.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtcafzoskv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtjtkedkme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtdysvbdnc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtojylbsoj.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtadossule.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtffrrlurl.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtdbmdkoeq.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtuwvzfooi.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtklozkyib.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtzyzfxrtd.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtwuquwugv.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtngxprgww.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtxkwfgbrn.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gteebiwygo.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylzbovlu.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtulzkebhm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtqerrvavw.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtivvwwrss.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtulpbhfnd.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtstuvceuj.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukbuvbuw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtufnrpcpl.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtyvvrsrrg.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtadfpqabw.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gthgbtfayn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtxbnncnfl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtghptnqzd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtqeevdsmf.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtulnydxnv.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtkjlwfjgz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtvntaxqqs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtuxaqrncz.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtzelyvthk.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpaeknpf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtugbxbfqd.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtqkgthvda.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtaqrkksog.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtthltnwgn.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtsruxetrm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtoylmugga.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtqkqvynek.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtbhjxdqqz.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtxakfsqwp.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtmuuptzwy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtovlitmpj.html


<!-- 参考信息 -->