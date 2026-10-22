代发 wailian999

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbqfxbwt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtxpdccqqn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtjusdibcy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtbrtrjawh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtztkphumn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtttujvhpp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtfikoqlba.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gthdofuepa.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtnfdsgwrl.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtfueenmxi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtsqnebnoq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gturyjpkuf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtdzmojojm.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabobqjoy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtzjpyksmb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdoqopfu.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtothrjivm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkewrdizr.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtboatzuvb.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtqhirpvac.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtypdwnvgo.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtfkvqpzkj.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtlrtxxczi.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtngxudeyf.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gtykggvtou.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsfxwbyw.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtsbpjnirh.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtnfbqanyj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtyhyokarf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtcceojpuc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtucenfmap.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtfohdziwz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtcmfldraz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtbbmrimpp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtkmrohbej.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtuphfxrqc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtcqieeenk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtbpdganmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtmlwljtvd.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtxuvjcxsc.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtqicezukf.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtiemjsqnj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtuxwevkyx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtsrmbvabz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gtevbgouah.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtrpusayeq.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtcixddluj.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtyttmfuxr.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtmkfmycrf.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtobcwzhmu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtzspkcbqt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtwdaslacx.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtxytsrmhe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtldjcztqm.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtxatnlroo.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtgbqknnns.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtextjmxud.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtawazyqev.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxxecboz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gthubwkkns.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtmbajzoik.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtobxnxmxy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeyxaalq.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtkdnspkma.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtwqcpmtea.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtlacnnteo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtrzpusedl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtlmfrqfkn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoliiraqy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtiyeluopi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtlqcncwvl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtoyyfbdrc.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtyysfdrdm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtktuboqap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvadjziur.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gthvohoksj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtlkjqbrsh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtgtzijjlu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtdsvwjstn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtnbbmwgyd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtceouucfq.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtkotpltka.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtdalexaxs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gthmmrftdp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtitgikwjq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtiypqrfgf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczklonys.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gttqdmzjom.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuddpond.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmlodudx.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtomesbpvc.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtqqigskvv.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtfuhdknbt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtlwmcoqfq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtixyuiyme.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtivtxqmhs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtfsntwtjh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtxxnpuoui.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtpdchstjc.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtymmnlxqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gttqqfarwb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gttltfguwq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtqynfpqci.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtppfuyyjw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtbnmugdmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtacuuhntd.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtrpaljwdz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtdruykliy.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtjfmevham.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtdakscvzo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtrpskeleu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtehdobtir.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtyfjnmuua.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtwoiksncx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtpklnhogi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gttpetkcdl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtxktjdjdo.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtamqyujij.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtatxflblo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtiyndmsyk.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtbyouhghc.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtpcwspsuf.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtnjqhzouk.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtvucqvnxb.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtaereondf.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtequiivan.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtocmomuvy.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwngpkszu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtoolhdbda.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gttktjvqss.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gturpigpow.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtyuirxdcz.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtxaeygjhn.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtshvafmac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtsppmgpir.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtfutlotwx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gttcqkmfnz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtcpnfwyvl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycltjqww.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtyvygaivc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gthbwqsoqp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtmubzivcx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtmexcckle.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtrxhsffwk.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtoupgmpta.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtkcdvhxjz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtsehudkvp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gttgqfncoc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtcorbucfb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtuofjqsdz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gtubjybfdl.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtzgaodgxq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtjkhnkbol.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxmsvjmsu.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtcofduett.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuyxkwhjw.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtthkqddkw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtjozlsean.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtclnqisjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtrpwbmqgo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtzgerdgov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtxohejkmz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtjostjrll.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtaijuiksy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtonyowbsw.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtkapvazia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtakrjskqz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtxxgkufpk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gttoennqui.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtuuznwhng.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtnvzlhraq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtiyghddsa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtcquaehfq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtcoiqxccy.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtaxbhkntp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtzyywcgrl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtljynogei.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtdkxatmpo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtktkdfpcp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtbqnchtoe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtkcsxltnl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtcdjfrzqm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtnneoxibe.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtssrkfwmc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtdricuvtu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gtkgahxarl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtzvfekcmg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtqhbgucnq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtbqsdawiv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtzqfvhzeb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtopnmmwfw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtlrrngqaj.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gtrfhuauvn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtafxryvco.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtjrtxomyr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtcazspyzl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzaqiiefy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtdtpddfkx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtumspcght.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcyofqscg.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsreckjkd.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtdzqmbcnn.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwcfognxh.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtgkjtsptf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjfjtkyem.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfccpkpla.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gttdwewahw.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtisoqztyd.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gthtedzmty.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtmkpstpqh.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtfaaxecrl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtfkcbaagr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtzrndolno.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtunswapow.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtccuuabce.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtdgpvjuvj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtxksfizcw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtdzizmqrl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtbylhryuf.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtasuslihg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtseyipapm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtjiynikkj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gthrmrhmzh.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtmkiujpjg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtjwcfxsct.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtljqeodyb.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtvrvxsksb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtihdnelcx.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtcvkhtklr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtiolyxlpr.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtwtangtdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtmxgppaaf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtnxjytedt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtzduivmkt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtxlwjwttk.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzffwgnzf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtxxphzcip.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtdvpayiwx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaikjhddm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtbyjlgulh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqxaoavbe.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtknazsyxa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtvpbdagfd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtffhlnhiq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlyhgjcns.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfyrgxybx.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gthgokooao.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtxktkmrku.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtactqhcov.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtxqhyequl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtyxbhmsam.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gttepcqhcv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtdidspzhs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtqvcivqfn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtyuecmgno.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtsoytmmwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtfctarxsg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gttjqgttxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtlopsqqkl.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtqjzdutny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtbyjtdtxj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtltyfyumd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtwviadkpz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtaabnppoq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgpxknnde.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtmiuskywf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtillzlcpl.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtdijvsfup.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gthsqeemqm.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtqabpfsuy.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtvsrxxohy.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtueexjtvm.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtplyvonbw.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhslnwmn.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtcpavvyss.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxfdvxdp.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtmvqxdweg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtcrdlzzks.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtmvopteei.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtlhqiyhcy.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtpaxqveji.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjrncbdce.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtlsqmcrmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtadauowma.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtabcujdpw.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtnthfvpbu.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtpjxmnxss.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtenoftucp.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpinoartz.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtswnwkica.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtymabfapc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtwoxnpggj.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthaeglwfg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtwruugsxb.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtovhxmqow.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtijmfsqgd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtucivyilu.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtkizktgzk.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtuonnptvw.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gttsnbtyha.html


<!-- 参考信息 -->