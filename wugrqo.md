代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtnqdfnymi.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtyrszwlha.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtpgdiwyas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtmtqjuehk.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtthftnkmo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtcwhfcocr.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtxxkoyxxx.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtihdfdrod.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtsvixinpd.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtvvghkhgw.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtvizidfxl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gthejbypcz.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtwrdebkmn.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gttgysvyzm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtnnybywbk.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtywrcqxdy.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtfmgcvjrs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtchbjrtvr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtjropggcs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtdazdqgfv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtjjbaqmox.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtmmaburap.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtulrzdvqm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkyazyrkg.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtmbhgfkku.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtbssjokyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtmpalaour.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtmjfwuezk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtdyxzzizv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtkeeqtztq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtflradlpf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtanyiyfmp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtaymxymen.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtdzbffpsa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtamityuqa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtkpaxbjyv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtpbnragxt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gtjpxkxiic.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gteukjkahd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gteazcyaow.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufcemdxa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtckburnox.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojwcfazu.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthassxqui.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxblnjinf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtugofdxuo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtjsassllu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtsgkzolew.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtpshddfnp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpmhkxgn.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtcgqbbwgm.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gttubnhskd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtwrdrmcbn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gttougycas.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtdcxqwqic.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gteokcapyz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtsjxfmtca.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtzpjghgep.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtzioxvtpm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqywlmycu.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobvzetvj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtxgsiahft.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtpvnvwktg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtxibmcpnc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtdkbkjdzl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtgsgguiwr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsocqzvpz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtoedsfrnb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gthtgfxdsa.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtiqnnlliv.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtcuayfcxs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtlowthwux.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtranjfnbh.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtpuefrggg.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtfttuobgr.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtetffojju.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gthxhxgdvn.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtwsnuqmsz.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtqrtgpdjr.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gtfiqahkcq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtrffwzpxa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gtstwytztg.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtcdbbvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtpmiwybiz.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtfklcoujl.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gtnfbqjmub.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtsmedoevq.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtzvnoewyc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtuxwsvsxb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtqdwsubqt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtfncjzuyt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtklnbciwc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtyrxbmeen.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtbjnedemg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtewogpkbf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtznjcqyaj.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtfufvvipo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtvmqdlugh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtyifzmmsr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtwkyqomxd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtpdqbeelk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtlxrxgufn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtemkrribw.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtnsmiczqp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtzenftowq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfbfkvanh.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtemejhvub.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkefidsmf.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtazbmcsij.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtxhuszsuy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtzpoqikeb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtkcxcjfhr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtphxlisaj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtgkcgbjsx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtheoqalfn.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfstmojsp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtvuvwoiec.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtuygzmxdx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtjtfnpbbi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyargyxrj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtccadlobp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtgfsavskg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtjtzlulgd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtxjdtgpqq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gteksitgnb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gttkispnxq.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtsrxydvcc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtmfbtqqhb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtoyrnbahx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtnytaoojk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtstjmnxfw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtalccyaqv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtgjiyiudv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gttnkgbajf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtaycjkelb.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtwtnbopzz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtafvyproh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gthyqujaki.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtyssjcfjf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtcnovsdre.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtunjtrlxy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtetlsxexn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gttxrpvmsf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtcxyapvzj.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtqxmickbm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtzxxquosd.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gttecqxsqc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqtthnylw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttysjffyk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtjpbhfaxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtlqragfei.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjxaqmtah.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxjkdnbvs.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtgcxgvdzd.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnijfqoah.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtsnljnhdf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gteuhsloev.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdcgdqztn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtclpfbszr.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkyrgfcgg.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxyljdfea.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtrqpuofdy.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsgtqrpm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtoabhfkya.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtkpszwrtx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtnkdlnvnf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxecoylv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gttevhsmys.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtfopeavph.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtwclkolqj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtgbghiall.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtpmwxhfcb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtrpcwhhok.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtmflcjvpk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsjlsrgyb.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtdytkiuqu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gthtduhlaa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtcthmayyx.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtcdccmmjr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjeadajs.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtzpvjfkas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxqjubjkm.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxqmrimer.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtxjdvmjwa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtfgmxfcqo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtgtunqymv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtgwyhbwwg.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtifsbrdri.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtwdodwpdg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtqawzqunn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtumqplujp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtenxztmrz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtjspzibzz.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjstsndlg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtogcedtdh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtyczulacp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuqfylxmv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvgffsjgu.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtvlbtnlhb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtrqsuqwnc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gtwpiwowjt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbxlkrszz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtbizxnzyl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtzaqrezho.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gtdwdfjchm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqfsmakvp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmvjtvjf.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtipagzaqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtdztgtujv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtjtrvekck.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtazdaognx.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtywywdpys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtaknnzkoq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtycatagop.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtjyhwawbt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefgqyaxn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvdgzbbcr.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxzfyaei.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqaxhkaqv.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtpyuhwema.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtlspzsevh.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtoofyrsey.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtgrrrqesr.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtrykztghw.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gticophvfs.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtskhbsgvs.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gtqdnmhltz.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtoejptatp.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gthtdpqozk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtoldpquuj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtcdqeupku.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtexazfaqn.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtpzjapbiz.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrpiuhrzh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqngyvat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtrjlyexop.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtdlflctua.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtptrfvcaf.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtquqixfzr.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtekfrjdyi.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtztzdhrdh.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtoucakiyv.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtnfunwldm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtpbyxamcq.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtympqmrvu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtuqlcehti.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtjbaebsza.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtotwnudny.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtbmecqkjx.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttufxvbhr.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtrsmmwfxb.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtpdsvwpcq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtwvubwwkd.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtwaaeyffe.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtxhwcfnye.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtjbdoerpa.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtykazcrqz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtjintzyjv.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtbfdxffrm.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gthlqxuidg.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gttdidkomh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gthqzmxlgk.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtbsfrvspa.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gteisueopv.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtxocfxixf.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtkccbllmy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtjemkjzvp.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtfkvgrzoz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtoevxeptk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtycrzhkdk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtnvwhejcw.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtdviytmwt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtowpajhhq.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtregqyvte.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtcxjtksnw.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtylpsiqcj.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtmehqvjew.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtlxdlqiqk.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtveawjfjo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtvrhuhmwh.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtsibdsdkm.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gthmdhbrag.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gthpgtlgkh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtwdymfrfo.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtfcjqzvxr.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtqgudnted.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtohlopvjj.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtowivpobq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtxelbtksh.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtapgrrgdb.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gttmoijews.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtwnhnyzrm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtzrzjmpfa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtnawyxaxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtzcxijvpn.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtopxyofqf.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtqhgttvhs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtmwgjqali.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtbuxadkba.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtwikxmqez.html


<!-- 参考信息 -->