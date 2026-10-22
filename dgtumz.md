代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtzuganxcx.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtlpsmktjx.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtmwgxipyt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtuqcjxerv.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtvkabskeu.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtrhzmwvej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtcpueixkx.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtwburyenw.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtvgyxfboi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvdzktxpi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtnuvrufry.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtfpjdxdjl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gthpbjjgkt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtitahwqam.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtrqaaxazc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtgwyqxvor.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtkdfppdcu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gthahkakay.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtihvusfvl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtwocemqmf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbdlhrpq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtvhnhzknv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtuhkkpkvs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtpvfsmmng.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtoelxhukb.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtqzqtiker.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmwcuxmo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtxubegerq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtpwpixopj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gthzhazrbf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtxbuwhnfq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxetqjjlq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtozujvnqw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtfwqxuebe.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtertvdsoz.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtznllmwix.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtlqhfyqou.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtomecpfls.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtkxftderc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtsfnsocgv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtbypiczzl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtphpkqwzs.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtbofziinw.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtfgyislww.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtfklqtqdw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtqvyoiiet.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gttddfypht.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtyspxcsjz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gttimejiey.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtnzmpqcad.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtfhkpcwes.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtevjvivws.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtsrgcjpie.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmhflciu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtdntcivqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtacpjrdcy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtfgarehfl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterbjecte.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtgsfomovk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtcbljfxgk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtmoxegenf.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtlewqmjup.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtptskddms.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtshjlalxs.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtdfodhxvj.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gteabbfxzo.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtwmgifken.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtbdkdlgru.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gterhdtvrb.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtcwgibwpc.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtffaxfljc.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtljgsvvug.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtcqwamnhk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtpwmgdulm.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtcirfynut.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtntqqprao.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtymavwtev.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtrejzjhjk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtblavvqjy.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtrmamvjxs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtiqzwzfoo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtnwncmtll.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtikiftazf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtnduxpvxm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtsuvjgidc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtwdjrekoq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtlrcvgurb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhwgujrj.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtybuqnkax.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtajiwfjrs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtgndwlrsb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtyffdvbbq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtdmdxztyb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtclllnqfq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtfdioacam.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtrzlvbqpv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtntksnqds.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttcxpgdxo.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gthwbghhbu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxjsyliuy.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gtyidgccbd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtdpgixnfw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtkoyosrxg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtndqzzugg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtyvcoxfuw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gthahczavw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtxhbsnzqk.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlhvptvlo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtvpuvfhim.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtrceomjna.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtafbttzsy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtwjaqtexf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqvsrakv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtfbkmdmqg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxijxcoq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtdsrlpcsw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtqjinixgp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gtfppijaru.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtxgardnrs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gttzpzzodk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtteadycyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtkbevtrnx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsedemsin.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtmxujzfil.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtbjefnldm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtsybemzte.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtjmwsxaub.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmivqyvmz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtrtbicigc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtzwxqrlbb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtnamcbzsv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtxhdsxpxa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtomuqanfk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtsvbznnvk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtjwddagag.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gthzrtxwkr.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtqxfwalqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtfieiozxw.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtpqvflqrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjtwpfwmj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtilwlwxlo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtlipswq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqxoulms.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoqshwxn.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthxlouify.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafzqyqmr.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwupjndfe.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtwptxxozt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuqkmsgd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtymwrjlsv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtkcdjhbyk.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtyoufyxyn.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtfbneojek.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtvpnzteic.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkrtthdn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtkxkubuzi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtgezvvciw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtfacbhnyr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtwagysxrx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtzxleveix.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtksmrcgsn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gthudhusfl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtyvutylch.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtkhyydnhb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtyniejfkf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtzeeqtboh.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtvwoarkwf.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtulixrynq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gttnziollb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gtfxpdomkt.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtmescvfdd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtfcqxknka.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtexgszmkr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gthtchbybx.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpktgcdcs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtbrultasf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtulzpcnag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtrxwjaxva.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtwpastlvu.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtekfvqjtq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtiamzwhyb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gtkcaxcorv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrycrrqaa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtjtpnogqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwrinjsri.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtemrxbnch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtckyoayjh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtryxbjmlt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpjeffdpw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgdzmyjju.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzqlbagmd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtrzdccovw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtumgwkqxb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtubqvjdmk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfstvqiqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gteusbeklb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtmvojbwho.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtyfvvpfeo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtcneoamnz.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtyedtbttr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtwbilgssh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtykbfxgeg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtczxmqmzq.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gttsifwijw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtqvuedzdk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtkbvheyof.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gthaieaimg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtjxhvazan.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtndoavodq.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtcojwlxxg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdkruxjnd.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtvxfpfosl.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtbemebywf.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtackxnghj.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthzffoydj.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtnigfdupg.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtmjsaxopn.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtbipxmpvn.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtvkxzmcht.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtckhulpge.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtvmwjmhsu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtncuppiol.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtfvhlxnwh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtpfftmttp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtxxtgwhqz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtdtoohfsd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtxmtuamrt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtbwdnznbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtzpblpovc.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtjiwererw.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtbemwvrgn.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtxlojcyfh.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtttydhycn.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtublydija.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtrsukodgz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtqowxihny.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtaehmdkyl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtgygvdvhv.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gtgdfoujdb.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtruydikqb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtwlvcomxc.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtbroewkmh.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtiypoiasa.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtaiudrfxn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtjfbylhvt.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtwtnokkai.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtkvbrjymr.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gteomywkxx.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gthyptzqvz.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtojnvlnkn.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtcabvapsn.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtbcoenkzx.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gthgpansrf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtblwllebg.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtyyyoieop.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtwsnphwht.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtgxiiwnho.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtwlipxqrn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjmdtoqaa.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtrikdckzb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtyevwbjzo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtoodfqupl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgzqevgs.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtowwbdclu.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtufmmooco.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtpqnyqqpe.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtuvjqnvit.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtihgtbrtq.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtjzxjhypi.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gthfknestq.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtgzgszfsp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtwadnilnk.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtjqxhvuaw.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gturyakxzz.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtumtougmi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtkdbdopll.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gttfrqwvvj.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtcukaufxi.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtbsikfzbu.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtejillccb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtdjkmcywq.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtiiuocvgr.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduqaabvf.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtgpjmuuvg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gttcbfeeab.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnvqdnray.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtxdtlkjjq.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtozoathni.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtuomasjqq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gttmawkwpw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gttpmrtizs.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtuhlkzqru.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gturacspfm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtgolaekei.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtgdoodexi.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtozkjtost.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gteefkizkr.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtqjiufuoi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomefqonh.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtihjmrzwa.html


<!-- 参考信息 -->