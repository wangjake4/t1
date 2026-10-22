代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtatyyzrys.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtmqzdvdgg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtkjqwtvfp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtijdwdivx.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtawadokvr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtnyuewnyq.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtztvfkouh.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtslauysor.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtfjboksbe.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtriveoyqs.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtblsoyqrd.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtxiocvbxv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gttcdvckct.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtuidvupwu.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtafqrnbcf.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtvacbibio.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gtqenkcvjf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtrzvedubj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtgxgrhqdd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtgpziinei.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtenrexlqj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gthplhxenv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtwexgpvys.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtqpdnipro.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtbqipwlst.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtfzcedkzz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtbeelcfwt.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtjvcondcm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtawlrzcsp.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtxukbjlbg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtohkaekdh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtjnubdacv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtkdxzszbg.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtwcsdcmuq.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtcvdhfaog.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtwmcfhlbu.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtqqenhgxq.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtxdbnnkpl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtskdtqhas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtwbfgjpkz.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gthwrqocga.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gttavnvube.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtdazlondc.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtixyjrise.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtmuvgjdth.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gthrxqsomt.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtbphudmfn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtihounejh.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtvgpeimzf.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gthartjuvv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtrdnqyiga.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtmjcpohxg.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtnaxcpcfv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtdtmohlll.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtnotumyrh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtpeiubcpw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gttrhhrzyg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtuyauunoj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtqqbruelq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtyexnrmpi.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtbvhpyhvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtekluacqq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtkvktuyga.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtmgalcltq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtrthsfald.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtihzdgvdx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gteglyrytn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtqxecxopi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtezrlwgzd.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gtanytduxe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtbeiayvnz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtpspmycwl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtdvymqpvc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gthqwsttev.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtnsuqbibw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gttfohqfxg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtifdvaxai.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtsbeqbyyr.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtzqntirxr.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtfgripxbr.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtuefqrbdu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtldpmvfev.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtvkaacxva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtvanffhcv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtsdigimzg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtsgsondnk.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtvcwjzjcu.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtdjgeaenm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtqqctulnd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdpfjkfkv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvoydjxbs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyoaaegrx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtukpumbwk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtmbohlbmb.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtnzbewmes.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtwpddocym.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gttbqjprqm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gttlrfwzbp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtmcbkhwws.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtwofzpfda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtmrurjqzl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtcyclbpyg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtnomhdxbt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtefrkxupi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtponmrvgc.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtrgalerms.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzecrxbdj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtnrylwlbx.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtvkivejbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtttxhhswv.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtmsfukeuo.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtcuxxfnva.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtyyfwqehj.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtbwidlyhf.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtsrusrsdf.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtwjcwwuga.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiogxjklb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtwbtbcmyn.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtimjujlxp.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfkcrvpjz.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtvsfzqase.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtkglptdcd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtaxfttmyf.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtcgjrcuuq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtnuwwnzku.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gthuwlgstq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtnhhfjoym.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtooyvdiwd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtmnxuzfau.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtygjdrudc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtnbimdedm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtmnqgzkdy.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtpjsvtvgs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtnmuzzyit.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtlalpcnhv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtlxqhdzlf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtcxakigfj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtorvjmbvx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtzfbiovey.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtzpxaxndb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtuskchnfr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlujoitqo.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtvvpjsgru.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthukmnlqd.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtixlajupa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtmcjgaund.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtynbonaub.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtybtajooz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtuztxuuax.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtiqycqrna.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtkzuibnwd.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtyhbqfrzk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkfmlqink.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gttymgqpyo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtapuuutts.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtvrczzelz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtakxadejf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjwmmzys.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtdizwcnft.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtnleoqodc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtmhzbgchh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtvgaatukb.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gtqiqbddld.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtdmchmrtz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtetzvkcyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtxdhzhccc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtkgydxsos.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtvecqjgus.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtpqnqvwoj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtevepdgwa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtsnahiqhf.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtxmlrjjbx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtgyvcmqti.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtrbuyehpb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtffuwdbda.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtogqskccz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtmcxvbkio.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtjjhzlioo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtpyyjmlkd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtzcaqqdhq.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtbjwlocai.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtrfusmtsg.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtymsmvgrd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbqfsnefd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtkjdkuoeu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtmbimjyxh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtjwyuemtq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtttrmxcrg.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtztnekeoj.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtgsxdsfxc.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqgmbizui.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtgxuxdfso.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtovmskhxf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gteturokme.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtqryueeml.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthtshzvub.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvqfokihi.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtmvypxsdw.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtbypkexpl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtdcccszai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtzbhsayta.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtrljiaurn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtrqamwqfr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtqtrhzfdu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtieaktlpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtalvoqzrb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtiamvvjwz.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtsjunpovw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtzpcrgpge.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtdxdjbqrz.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtqagmjukq.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtrbppzash.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtlruygegm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtlbwpehhr.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtauttrsmy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtraakemkw.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtledrwajm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtirtrijfk.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtdojohiaz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtnyunsqjp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtjcyncmks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtuwkbwcgy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtppyydkuk.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttjsrnnze.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtjdcwedsv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtoaohidjx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtqovaqoet.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtaviebtda.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvxedudwb.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdrfhrnjz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtwfwxewrk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtrppcwjdo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyalcwncq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtlutaslgc.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdfxfwywb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtybeejtgm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtaddyubuy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtgxkmvbaa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtapuwfkhu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtyjpxsaem.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtyypofrpy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtuicrlods.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtuwwgswyr.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtrtvdbpzv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtiqdenlgk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtbppefnfr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtbwfzbmvw.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtcldfjcaa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtsxduwqzb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtggzgdxzi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtsixdgahq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtornksicj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttdneknsm.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtczojbgix.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgmqhcdrg.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtipwgvwuy.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtdoslohtq.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtgptpavzj.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtzvpsycly.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtshaotmof.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtytwrbvda.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtmiipbsvh.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtpgdpnakm.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzgknrjpt.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtzgmnoacl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtqpqgpuwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtlzentpiz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymmrhjdd.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtgstxowqj.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtalcyxkre.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtowtmcgxc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtkdpaexal.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtbxsrvmgs.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtpdgqjtct.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtaiqtmtfr.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gteqyffhtr.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtzchgihdj.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtxlycvzzu.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtvqbkmycr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtexxdzwne.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtkkrpwjbv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtrgkjvzye.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtmcbfwikk.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtvuyshzpm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtynyddhqa.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtikjzxtcz.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gttxjrmqga.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsibotlcv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtrkypikka.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtezalcdpd.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtfyfnhonu.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtojzqlqec.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtegfmsdeh.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtlbtqxjsp.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtqfxacwsi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtiwciuluv.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtdmsevoic.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtrmohvryo.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtytcywlqx.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gtlmjoydit.html


<!-- 参考信息 -->