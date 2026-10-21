代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtagtznpjg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtzbypdjju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtatpanvjq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtzrzifksk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtwoudsknh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtknkfkbfy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtidgwcxgo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtfbkyhejo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtgcwodbfm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtnolmkkeq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gttwkcjzwd.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtnilgwuyj.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtqshqobwi.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtxzzdxcru.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtjxsuoqxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtqxdzdlvs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtzmlxfqmw.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtkikktdkl.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtkrknoyyn.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtkmwgwkiz.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtzlogtspj.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtiqrisqno.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtkpmjeeej.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpgbtcky.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtaoxcjvtt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtomptuqbf.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtqpifjatx.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjhixsem.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtrrslrgqw.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtpbofatcb.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtsxfwochq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtrvjaojre.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtwbccghyo.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtxmpamytf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtixivseaa.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtxuvdwuci.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtzqzgnhgb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtzxzpuebp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtbkowkpzq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoinprjj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtxvruzgmd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtezypitss.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtmbrrnxbj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtletxfmvw.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtqsglnrcd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtxirmlwgm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtbqrnxgin.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtacippkmn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtjvovrzer.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gteodmtveq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtuxqcropb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gthwgzeamu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtiexjzrhy.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjhwaapq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtswsxnqgb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtujwckorc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtvbvvigyq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtdmwgvurz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtcynfjfuy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtqnbxdzyy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gtvculybbn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbbsznnr.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtwnpcckje.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtzivimyin.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtptwkoabq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtisfjurts.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtiufggwzw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gttwnbklqk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gteazgijzc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtkvmtcsxx.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtsrspaedb.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtluwiyvwg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtjgspnlwu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrpzjji.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtdlvlsvai.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtmwesusvf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gthzacitlp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtgwvrskyr.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtwinzlhzo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtniowwgct.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gthgrzfech.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteojtkeq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtymkpcjcn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtkbsjudhu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtwakdhsxh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabplbhsk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtpcriwhrw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtubhujnlp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtkmuncnoc.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtguvyvrqw.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnwrlrfo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtmrifkywj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtdrocyijn.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtsufluaqx.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtuikhyhba.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtlamrdnhz.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtumhnkfbt.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtusvbbjth.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtbbkynhcc.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gtaouuhszk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtwjrvpwzx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsrdvidsz.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtyrjruebu.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtznirhwat.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwddpxgek.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtutmzltyi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtitxqxdwo.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gteudlkqyw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtbreotzrq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipjfmtwo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtwybedyjh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtkllmdclp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtuflsvmar.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtfnokoaan.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtohxnkzro.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtmeduimoz.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtoglhzfzu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtyyhaobjj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtvhlkrcxv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtvggfgrta.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtanohvqjg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtavfnhehy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtekwemcwx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtxkdbmwoi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtzaqpbazq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwlbictzo.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtchkwuvdg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmsvkkbks.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtnqtimbdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtgbbirzws.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtwuwjhomz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtbkiffccm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtadgddlga.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtxoezbpno.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtclwoccbe.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtudpapxxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtsnxaxgun.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtqhzyuzwg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtmrtbcuit.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtmvadksod.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtueyotfnu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbzygwpra.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtjmhcbgsf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiojqgale.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gthdnnqgbj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtatbmsekw.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtfmldqvbf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtgwhdmifw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtszhipwgo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyumzafz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gteurahjlp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxgyljvk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gttteejssx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtmgzpbzlj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtlfrdvuer.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtmqxfojqf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtofzsckki.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtmfszjfhy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtflbcoevf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtaexwwvmz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gthlyrhqqp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtmaxjtsec.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtmqewisln.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtufdryctx.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtkzeanghu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtijzltuvp.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtcovrcsfa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtygszzyjk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtsvsxjuph.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtlwwnhpnn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtmxfkuiut.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrfpnkwrx.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtycqegymu.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtbdpmgioo.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwcrhnswk.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtbabrirrs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnyuheqdy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpupyhzmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gteskeogry.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxdxytjhk.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxxyfxadw.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtnpffqvve.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtvnvopiyj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtciyndpae.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtpwjgwsit.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtcswreurf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtqmzlcyrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gthjhdmdnv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtgjbegenr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gtbduijjma.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtyppcntkz.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtkwqkpqqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtwcbktdoq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtkeisjhfv.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtogtaiwey.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtiydijqya.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtfohdrtei.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtdqbhvikb.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtbeikalez.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtmtblummz.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gthkbeygqq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtiumotcld.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtccsnvatm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gthhxbwkdr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtmyjlltsd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtpqsesdol.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtwoyyixeh.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtiblnhnwk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtkzlvtdef.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtrfmgjpwl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthakcixvf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtkbyusrxo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtbjzpmkzn.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtxlrkahmw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gttlkapguw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtiiyfpudj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtibbeazkv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtvxkcyesz.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtsllytmbt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjoztphvi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtusdwkxlx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtoqovwcjj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtuvozivay.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtjcpwiklh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtsawtqszk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgizufiog.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtgimfuknf.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtsbhleizi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtjyohfsjg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtnsgfwcxn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtmedepufk.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtizdsqolg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gttcbgfryg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtiekfkmyk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtcnbzpasf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtalmlpmck.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnwxzwzcb.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtlvbtmkgc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtprxtrzwk.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtcyurtfoc.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtylidvhmz.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtyyibzcby.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtlmocukhv.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtkdyhtfci.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtwmxbtvhw.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduqixllk.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtxnggyuub.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtecyckdvl.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtkwlswxat.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gthdxqtpav.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtcttkhvdq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gttnlnncgl.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gttuhpdinq.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtdpxkqgfu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtrucddxvp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtfrxvgnbp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gthpwruqhf.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gttwkiawag.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtddvptyux.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtqntkponz.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtnlhkrbgq.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtgwvzycxm.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtmtzvvgak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtttgddnul.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtyjgszugs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtrhltqesr.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtjmdzuwzd.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkkmetxd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtzhbbhvui.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvovrobmv.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsdsqapay.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gturlduagq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtcwfshcfk.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtkqohtuzu.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtafifzvrq.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtnkzhtrpr.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtyzsinlwi.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtdwtzbdaf.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtowegdnui.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtmogoieve.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtyfdwhtxb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtsuygxkqv.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtgbvuwgzg.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gttjbheinz.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtygottbbv.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtpaxdihsm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtxcqallws.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtqnbyfgca.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtwpmkvqeu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtubsmeqow.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtksnchurk.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtatffjaug.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtxenytrzr.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtrbixbcxv.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtelrbmekx.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtknocxpvr.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gteihiuluj.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtzjcgieea.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtjiaomqcm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtyxppvclo.html


<!-- 参考信息 -->