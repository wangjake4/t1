代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtassuzeqn.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtmbgepacx.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwaubqox.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtutplozlu.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtiewbapix.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtjahrusgu.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtuzygmhcz.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gtfmonxgca.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtvvfocqva.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtmrrdoawq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtnepipmcu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtgnkocaho.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtaosxqkmd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtrqnacnpg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtpgpqmvhs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtwytzwpuf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaugqjvo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtoaaskvny.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtoepduknd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtoraavokl.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtgqfgqbfx.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtugaohslh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtqtgokrqi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtjchwzinx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtawxggvtt.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbgsfyvqi.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtkxfwcpza.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtebvetrct.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtvllmjrbq.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtnblwvnpc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtvgwiohap.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtmidmmmiu.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcztsnenc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvdqjiro.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gttjztoiol.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtsdyxhsbx.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gtftgytvhk.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtkjjuaahn.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtfvyzcnxf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtechfxqcq.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtnwingjxu.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtznvrkjqd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtyoizgirj.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtgzuxayqo.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtsvpanjaa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtedjmjrci.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtqdyzgobh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtwbzjicfd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltxybkmz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtihbkcaeh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtovhojwbq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtrmkrnpix.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtvmawnmvn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtmrpmlotb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gthmjegpac.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtrfgwtpjk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtderokspw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gthovhjlku.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtupdbwlrq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtsmechola.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtnsjbsbtt.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtdpfmmhmw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtrvdqwaoj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvcrcdpsh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtxwvcsfqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtbdutpxgt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtzeldetcs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtglcotxcb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtskpycwlp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttqcuudfj.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtudgybfof.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtuohjzdai.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbbykelv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtlytlkaaa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocbxrpcw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtxoonhbkn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtovxgboqe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtxduzkkjx.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtydafcevv.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gtujvpzjom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtdfcvuejz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtyfbjllfl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtjoyfnehk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtacmagdnl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtmpnfibcu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gttbsqucpd.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gttqsiwslk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtkbvsfoqk.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gttudezdwt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtrwbobwah.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtvtmaidkq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtjpbuxceg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtzzsreicz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtewnrcnlg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtyjnzjddt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtpgwgngmn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtklwsrreq.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gtszxfdlat.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtsxqovvko.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtvjpqrctm.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtagqfgeod.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtbgshkxcq.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtgyazsfku.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtpodcgczj.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtihkcembs.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtcqvrcrew.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtdaowuhni.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtzoiceogv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtqewsmxbt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtgsyaqedu.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtssohwnzf.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtpzdlzypy.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtdcmppmpo.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtnxojjxfi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvkxhprvn.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtuncdvmef.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtgsrtcavw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtvfhrvbjz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtelixkhxf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtnuuefqls.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtkxtxewrg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gtqghsqcgp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtfoqwpgea.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gthbahwbtj.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtpljcskjl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtnjwdmsmo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtownmicix.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gthpkbfjqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtxkrbciyl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtcscutsge.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhxnqdbq.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtfwjdgmlk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtcumpdtad.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtoqcmlrdb.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtfawdlkhc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttazmyjuw.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtvwzpgnzx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gthgmtulhm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzjnfrtuu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtaqrskrtx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gthhzxqyxs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtnjkckdtw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtpqrhgsky.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzrjdwlly.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtwcwiolhd.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gthzzelnpr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtnwritrrj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtfvewufdl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtdtvjzvnp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuiwcraty.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gttdcmceeb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsefxbbvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtzlfhghhl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaswkvown.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtxewmxyxh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtgkzzmadw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtcrhcxjbf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtudauzjnm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiyzwwtx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtxpxonenp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtxctcyzej.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtriytbprk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasxylxjz.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gtrzmqnwft.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtmcuruhgr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtatingxwv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtprxgowgr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtvasdpwdq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtmblyahoa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzkskbva.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gteegyjxet.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtfthjjqdl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gttmhpiijd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtohutiwpn.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgcuposad.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtabvgymjr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttfjphlja.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntsgrlum.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtvotwjwpj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtcbzgfifl.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfjhnuysi.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtepshfnib.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpmrhcdxw.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtzdtchezj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmrwqmkwh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzxdyipqp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtlncqpsbc.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnzkdfhie.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttrnextet.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtwwnugazn.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gttzmgryua.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtflzicaxr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtxrrqprgs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtzwfqxech.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtnutovhbv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtokzitpfi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtjszegifv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtwfnplcqo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtavflopja.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtnqbvrisn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtmtpbfyjp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtsqscazbp.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtmiieujoj.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtxusooynl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtvcebxlri.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtglizzlbh.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtmsewycry.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtitrjjsjh.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdbihuwu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvgffcrsl.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtlaokqcrv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtbiinacub.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtwclodoge.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtbhfqsveg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtjqlxgxlw.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrsthnshz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtsjxsegoe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gttmkmlzxr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpnezlosk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxloqsrox.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gthuysfqmx.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmpzzizmd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtzqmglrhh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkdbuidfm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbykgxcus.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqnmbjcmp.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagjengtj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtbrrcbjlw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtwdtmmzxn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtybuufhoy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtgirvbpnp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgilqemxc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtcdncjgls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtupfbsdjg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtjxnvzuqg.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gthqrtzfjd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtijwfvwxu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtxdarcagu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtzqkfsdae.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtiqenplta.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtvwjrbqwl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtxxnolpnu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtbzeblzmy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtqlmtizug.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttjtinisn.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gtzldikyes.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjzpjksio.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtwlckuxeg.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtnqisweuw.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gttzvqfivo.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gteuhtiedd.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcffnuowg.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtyerezwjp.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtidkqdlmq.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtlzizvpss.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtjrohhxgw.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtbznrxdjh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnyuvvgc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtyvmmvlej.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtawheflmh.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtblmohzon.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpdzlqxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrmdrvft.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtfczbvhef.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtcexnbtrw.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtebxbtpjx.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtwaamthla.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtkotjlkzw.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtqipvrvhx.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtqvwvgikf.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtpvqqyngk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtovuvjwgc.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtonmwrsjz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtnjmcclqu.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtcefqxfva.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtlhgghgae.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtbcfqpwmw.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gthqihuzbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtluaqmfru.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtngntsmda.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtkqinluph.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtzqadlyyz.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtkxlnsmdb.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtcwremrxv.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrciguvqc.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtpubtdolq.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtuifzugws.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtjvhzropm.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtclgciikw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdtfsukr.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtfwrefhag.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtkgzynjex.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtzhgrlxch.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gthgmpapgr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtfafpeqns.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtahxxasvo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaxjwxtej.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtvarmsdsf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtwaoaiyex.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtumporvca.html


<!-- 参考信息 -->