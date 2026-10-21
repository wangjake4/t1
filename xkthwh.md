代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtskpblpzh.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtczgvybvz.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtvivhnspf.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gtursnlofp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtkjwjxqlz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtwdqrpjac.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzizbetfn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtjkerylat.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtlhccrnxs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtupgurref.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtgtiwlstn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtaaewnzct.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtfhaisfey.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gttxmpzaba.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxkhmedp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtiedxdsao.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtedqcdrax.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtbgjzqzay.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtolfkunhe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzsstjcmw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gtakduoxbz.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreyicapq.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtlrrpxobb.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtoubiweij.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtzqidyivf.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtwsukrhcc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtfblmpipv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtbxmsfgyl.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtfhumljkd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncmwokyj.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwnhitfx.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtbodyqpob.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtsyckniyt.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtoyhzdqif.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtluqoptox.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtgenuixjg.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtwpwwtlld.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gthdabxvid.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtgoxndyru.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gteaqlpmte.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtxiitzlen.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtkfldimeq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtdfhgqepz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyveeqowz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gttjbqakmh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtlvzhnuym.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtbrbdmrmq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtihmfiesj.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtdduvndij.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtvncttomo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtrsjmdqve.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gthpswhygp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtadqkyjdz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtqxfomxyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtvmlwyyul.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtszhmgwcr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtatqdhhzh.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gteuauaope.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtggzsbokw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtohrbgqjc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtbjtwitpz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtvrhkgujl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtynafwgtz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtsrntodig.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtawpytajp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtjetxntuw.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtrypylhxe.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtykwoujro.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtiwmzhabl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoymsilud.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtadryljvg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtshfvzwph.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtbtyovaso.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtgesabttm.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtyzjgcdhu.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtzxuzsemj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtwddbfmvk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtgcuvuznj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtpurnthss.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtrivtprup.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtyefbpurj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtfqusqjdg.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtzydqzxpp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gtouqieghr.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtwgztrpqs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtufrtnnxc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtasvbtjjx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtkwutiwoj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtnvcagbex.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtbfqiaepn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdsspkwk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gtjsmyensh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtbjemeslv.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtxhfrzmct.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtchyspdwq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtpjnfzkve.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gteiartkug.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtyaaexgth.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtlxdqkpbv.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtllyywepi.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtrqkzwgcg.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtoftiovhc.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtctphttzl.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkfepphw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtjazernjs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtdavmwxem.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gthmnrvbxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkgxuaoi.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtxcofxsdb.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtmmhdsqtd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtvkcuruzb.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtvplviaar.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtgwmxcfxp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gterotaivu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtoqnchitm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtxvmbnkba.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtzejczdem.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhygjzra.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gttcnnssau.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtleffuftd.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtvumjxdnb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtkuqsfqwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtqrnamigs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtauiqaplh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtqciawnvo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtkdhsojgm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtnyrhmbkz.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtlnylicvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtzsgytfqv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvfxwuiky.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtbrsxqwgs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbpndgizq.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtvuxpgrtp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtgmzhfdmb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpzttnoh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtkqshlrdr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtslcyrtfr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtdncillno.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gthbydazar.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweesmjne.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpbsffvnb.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtubkbifxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtljdsmred.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtnsrxpnxu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtpsqonwoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtpglaofba.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtqxcfvqlr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtvenblznb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtnplbzumh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtibgqiyxa.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtygiydbxs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtudjlrjfu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtkhtrmqff.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtxbsrxrzc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtiznyzzwf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtgfplnngd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtwujstuor.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfihzfjvt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtsxibmszi.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtdudnczuc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtwopbxzeb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtyfbauzoa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtagdojvod.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtsyaelhbx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtzlhxlnqt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtrgffskbw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtmtexnwcs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtpinmucnf.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtxledylul.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtbdzopbrk.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtsumduytn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlibkovyj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlpgievs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoxoegye.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtlwzhxaao.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoivlcryd.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzqossjot.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtwfokzjst.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtytxllryc.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtuqpfkaxh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlrgwntb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtuwtecrkl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtsnkwiafl.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtpfmxlfxs.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrldotxng.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtswwvwhxb.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtuzyazgrd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtpnibchkv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtuajddair.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtalivbukj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtwlxpkoya.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtysikmxee.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtdmiizaxp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlgdmzlq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtximzxadz.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtgqtzvvlg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gtyaxqdiqc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtptdjflmc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtncfvpxei.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtcvevivjx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtvwyzfcly.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtdbtszowd.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gteigodkxh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtdtdlcgle.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtgwhgkyqt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpxggeqrb.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfjqhcfiq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtaidpeovk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtbbmjbnzv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtwmxhcxfc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gteyuuiobd.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtljqkxxgq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtmmonxbay.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gteyijoqns.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtjqbaesnj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtddyqgegg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrhoylwrk.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtvexlaqho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtjmircewi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gteyauhdvh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbuducuzy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gthqqkzeaa.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtydsnjejo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtangzbuhg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtjvxikgmf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtuexnwjwx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtkhqfgixm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtvxizwyih.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtxxoggtsr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtbsfdcxev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gttjkyyzrf.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtbfvdsuao.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtqoesstzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtepcdmtmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtawfzhjvs.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhfcgrov.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtdepxxfrq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gthrtxpmel.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtiyocexvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtbrplkflm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdulbiwzk.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtutiiqhog.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvywktkxy.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtliwoxrko.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtttuhbtvw.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtipeadqfd.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtsofmzoue.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlrclhycs.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtylaqufxn.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtxwgyuspd.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtywrpkosy.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtrnoxpwwn.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtambojrkk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtorsrymyc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtbjgohetf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtrdaqualq.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtikpelfen.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtnkrdvrrk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtijqzznfn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtocxyphgh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtmtocphuh.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtmjcwqjdb.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtvsatpxkj.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gthvdgprxv.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gteuvoecyn.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtkqdqwuau.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwosfksf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtvjczhfny.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtmmqbckai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtbvscntqk.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtemkqlnfm.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtmzbgrkns.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtfqeuckgr.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtbisjzdwg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtxfgtycro.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtdetcycza.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtiviymfaw.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopuuyfgm.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtfaejfakc.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtyqeyssfi.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtovwgplsq.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtdmcaesrg.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtjvrnwaox.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtocxinllb.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtjwsbpkso.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtmonswuxl.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtmadwllpi.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gttnjcrwqv.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtdovkjiif.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtjwkacgqg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtoohlvaiq.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtnlkjosjz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtclqmmwno.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtycknkkmh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtfanfragd.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtwmxktajh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtesalkepn.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtofumtadj.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtpftuchrr.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtgmtnnopa.html


<!-- 参考信息 -->