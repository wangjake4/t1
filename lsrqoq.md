代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtnlbmvugz.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtrryktxnx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtjqapakmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtajxalebn.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtngjixwzi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtledtbykx.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtnngamwdm.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtcrqjytyg.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtcqxbsvak.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtsdwystte.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtzgztlcsu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtwenbmyau.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtjfhxjivm.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtckwopjwx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtienrxtee.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtioexaoxx.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtxciyhjsb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtheqmtuyo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtwtscplbk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtkvcnuthd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtphwgwgyy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtaaravrzg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtpylieswk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtbfeelkef.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtcfvmlbhb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtjhybrtin.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gttklfngcl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtovwjduep.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtvqzzvwfk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtoaysnvex.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeibnhag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gteomouuef.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtckzaqaev.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtdlujttfm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gthficxxqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtfpdioblf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtpagbppcn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtygbpnuvd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtmprhtaqd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtxniktfzs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtuiqrpbfk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gttrplyois.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtkcvyxkca.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtdygkkivb.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtgurqjqwy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtfpksmcbb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtyneisyuk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtwpmvnqit.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtbsgemngn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtgrfnffit.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtnabctmno.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtfpjlgckg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtnogesftg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtteanaxff.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtcpeqrnlu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtourirgvb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gteeqcugiw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtsfpjklns.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtbxefkrxm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtyabdvfnc.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtkqljkyoh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gtnccwlxuv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtapbjtywg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtoaaiiuac.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtqrqtsdyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtpwtcboeg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwchizra.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtlrioztbj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gtvvlloazl.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtezbgkrtp.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtzotluybf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtxmsuypup.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gttaxmlzxa.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtljsmmjbc.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtxpvxbiex.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtfteaaqjh.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtdglwnjxr.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtmwuondgc.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gthitiqzob.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtmmgggnoy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gthcsyfshs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtdicdmguz.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gtiwpmshyj.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtiqeivcjh.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtqxtqoycp.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtipuljecr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtvlyubwwf.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtlaxsjooa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gthjtvhuql.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtuehdpskl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtmxrgsbcq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtshrgmkgi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtqnlzzyzj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gteguvupij.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtzhtagrhj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtsskdkvvx.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtmvbunbbk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtriywurdu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtjkawizph.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gttvpkkydq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtabebvzpe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gthzxofush.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gterpjbhqd.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gthakvzmql.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtbuutdxtk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtleagysxt.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtihyfwnps.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthnjaygnt.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtaprzgvsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriprqmau.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtqfmxuqcr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtqgpggtoe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtulafndle.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtufxenuzz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtgqsspzoe.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlwvjuayw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtadylamhk.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtulwarjlv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtkywbppnc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtjgjymwgl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtbcbwrgjm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiulkgdwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gttlzxrvrz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gthzzseqew.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtwtvjpwzp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtnpucniou.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtmkyaeqpu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtxnorjxep.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdwhwvdr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtxzjdkfrh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtxonocbdc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtlrqpou.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtkxozidsb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtkxctuugc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtggwbcrde.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtuueeihtt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtszowelow.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaixrrta.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtqwkcgmbf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gttzipgpdf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gteylpxbpb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtppviougr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtleiuvzdw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gthkcrwwki.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtapuqlrxt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtpidwvmrl.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdewvaeke.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbrdjbdku.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfjobtvqc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtxahnhbib.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtwyexsabh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtohlzcbkt.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxezvgpdf.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtshbawydt.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtvrcdjrvn.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqteptmlt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtllgmfvun.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtupzivbit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjmjksif.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gteawqfisa.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtznbkovym.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gthygfxqfl.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtmyaetolp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gttepvovrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtfmxhfagl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtypczndjv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtobounsxy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gttganjzds.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtmvyzecxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtczexrmha.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtyutihayz.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gttalvoxnc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtjfcfkhns.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtokuaskuc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtnytdbrjr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtfuwetkub.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtgyddlbvf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtjgbtjxuv.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtnbeojten.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtzkqcjevi.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtierwlsiy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjykxwcyr.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlgiivuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtzgwtitkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtxeewbpyr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtpcrrqabr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtbnelmeug.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtumvgqoni.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtpiuoycmn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtbhloyrgg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrqidilyf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtdqdfagzj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmlqgmogk.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfcfpubzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtbgvcvuln.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gternemgft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcelremmv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtafobxqis.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtliyimtqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmqptylv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtztkjywfb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdvomccop.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtertznccg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtdwesjwfy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtroromruv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gthbyqvwer.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtilsaoxll.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtdibpfqah.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtgajzrfib.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtywpqgicz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtycjqufyj.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtlvufnepo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtsbqqemdt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtbmcqhkgp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkqrucef.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtlpbxcoma.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcvutuxet.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtnykpoooi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttrjkxfcm.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtkmhtetfs.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtgxpvxuzt.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtqtkhaxda.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtopmbijia.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadunshce.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtkiilxebs.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtixdrqvzc.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtfvdqsmeb.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtkeqnoutr.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtchfpdhye.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtslumempk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtpoiplvhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtfmvedbau.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtainsoijb.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtkmujdvdb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtxxcytegt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrarsrbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtzmccbezy.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtsnilhilp.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtqevjnylo.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtwiqhbntf.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtffokjmzl.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnygayxo.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtsetgquzs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtvbzqgnlo.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtsyqpbdca.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtdkbpjszz.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtmvruggvk.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtepqpmfru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtvyetwbhy.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtfjfhlzpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbntdejxe.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtrqiirkyj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtulehbewo.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gthjwzjhfo.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtmyrudlgd.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtsrgaleni.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtjwblkhwx.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtwomelmzj.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcomoizqw.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtazpfzohs.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtsgaandax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtrtbwlzlx.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtdmrcrptc.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqmaqlzjx.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gterociltk.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtztmcqueg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtvroawleb.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthjoczisp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtmakkctln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtxlhpqvsu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtkzacdnfp.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtjplxelfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtltwtdebu.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtxnjghwrc.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtkfpbqdeo.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtidayzrmd.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtvmbvuoiu.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtjifxzznc.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtnxdaawph.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtxdpyjuvk.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeozowww.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtwqsmahjh.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxnaymyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtjazzxwwt.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gttesfpmaa.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtqedfbbgi.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtfyjyasvx.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcqhrekkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtfakazlil.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtsytvidbl.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtxulujnta.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkqkyojs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtdelswfgj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtclhcypun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gthmduzjjm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtzgdxmrah.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtyteltehh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgikriolo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtnazxomcw.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtwzanukii.html


<!-- 参考信息 -->