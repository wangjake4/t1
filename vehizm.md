代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrarjqeym.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtnncxiowm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gteypzuxvm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtogcggeow.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfvdzfwz.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtxwzabhuo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzitrmwd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtfdqdtkti.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtvwkhubjb.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtcdingzbd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gtkwwhfwmp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gteiiqqfsp.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtbapxmnxo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtqbtnvcuv.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtjmmvwfeu.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gtlcbicgzt.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtlptcafxd.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtfwpxbcbj.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gteogiqxng.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtifvbeqja.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtxlmspapz.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtrtwenmxc.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtvhnhgywe.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqtketmy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtgsbeqtxr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtsclomfhh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtehkhqbft.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtpbablnqm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtacfkcmat.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtyhxuahxq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtfntunhss.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtxkardrjc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gtycoluibu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwpoqtep.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtwizadoiu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtxsybucop.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtsdydngwm.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtxkwfrvyr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtmhplohon.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtsktuqwyx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtujyimxkd.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtwbrnhzxt.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtcxdbhanx.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtphubdibg.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtyyxobglh.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpysuphzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gtponvdwkn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtvwpmaklz.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtmnzoxkpn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtwpaevoiz.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtbhdzwpwm.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtxscdamfh.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtfxqqgnel.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtbzyulgpz.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtfogftitk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtqbvqmkmj.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gtwhqaoovw.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtjddptafx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtijivmedu.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtlzjddsax.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtntuakvdm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtfwhzqffh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtxihqowoh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtetleinyf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvbczulzh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtlqogsloh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtvmdncctn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtmplzbdxy.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtoevlrynz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtcmbmkxmd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtjnzlivsd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtowvahzdb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtevjnwhwl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtxjcexori.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtiwwxezmj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gtegrtuhvr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtlobhrhej.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtybhxfjmy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtefhcsvdv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gthchjfccg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtuufkveid.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvmtjwpq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gtijcfnfgb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtoijuleyq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gthwpvjcfg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gthpshfcam.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtxiqxxehh.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtvbkplqwy.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtthinxabn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtrdgnvule.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtmxnejpnh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtqsoutdzm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtjfoqsbqw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtbzkqzdju.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnehqyzwq.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtlccsjpxp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtvbseaohl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtgisuqnda.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtpupcdynz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtzyclqkwx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtjviuwnxb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtthvzdgwa.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtfodkeufj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtwkzfsrar.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtnnqfqdwp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gthcaaaslk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtntxlhqkg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtlabhfuwt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtvczwfgdt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtiexjubjc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtppazlmwf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtsfhupvmj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtoytkukbb.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtmlbbrmca.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gttftmuhgl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtzduvkfng.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtjxuczuzj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtlsfqtkmr.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtsbtelrlm.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtvjssrevc.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtfmssrmcz.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtkxkzoyho.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtcihznmls.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtkeaoofth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gthwftntps.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlebflyba.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtjtekazlc.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtukuriqfp.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtslsbylgu.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gtsyyndvvx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtvunlokow.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gttgcvetoz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtmvcgmqmn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtuntbyvjw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtkdqoakjn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtfetcubaw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gteyhngkks.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gteocbqmle.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtvqqiimds.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtfwwqptvw.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gttpaqqpbg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtfytvsrwt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtodlumzek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtuqjknmpq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtfgehqxqk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtocqhqcim.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtamasxytw.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtykxoqrsa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtwnymtxab.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfkgcvnug.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtwfeynyws.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiddqaez.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtzfwwjuvt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtjhqjehqx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtoeliunlw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtlcpzfiar.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtkhnznmwa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtbfkllmad.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtsfkmgbsv.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtysjrenvq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtbmfzirht.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbybljix.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtppfqoezf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtnsrmvcie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gttwonewca.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtggpmxbgw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtxxwoqftb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtovutdjyz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtidramoqb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkzumrhx.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtgisizdot.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtojxzejkr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtqvokfvuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtjslzxzoi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtfbxfqtna.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtetxvgsfn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtrskeilof.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtkjnzedru.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtjjpnnoou.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtrbaiwnul.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtnuofnrnw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtpxrcifwe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtvmzgyqwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtmxughxkc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtvmfhzuam.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gthdxwelwv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtlzszidil.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtxjsinude.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtitsnaydr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gttalmavsq.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtvjbwanwv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtemlwoeli.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyxrjrobr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtaidnrubn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gterimqyek.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjiketamc.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyrnnwgur.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtvnvulibp.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlztsjnkp.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwujwdwux.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtztxjzzyu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcpizobgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtjorggaof.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttxnieqmu.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyxndptfr.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtunktggsj.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtbkkkylaa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtzuktdohu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gteuxrvvcq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gttimcudqw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtloleyjpm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtnephdobr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtuejuaxsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtgscjzhfc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtnfqwxmmx.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtxozbtawf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtaqjxhnpn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtuooljosu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtvynwkzwn.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtoovjwwkp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtzcpvicmo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtguoertlt.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtmdzvvhot.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtwtjqjuco.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gteoryfagu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttbrhtfka.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtrecgpfzg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtqueqeoqk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtrsqpofef.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gteeflzcle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtirzfjvfo.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgplztege.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtkiezvjke.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtcxtuucnj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxrtxhjlu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtwkwpfwiv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxjzilspg.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjpdwezqa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtvkovldum.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtufxolmap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtempphrhh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtczyxpqgt.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtubnamgft.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtstwwavqz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtnijxjgrh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtrdaxaxhc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtioeejncg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtjmneswvq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtzqsucxyz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqrtjtroz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtgspxjrsz.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtsgbxmiqm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtxwtyuyiz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtnmblumkb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtohoxsdpt.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtccpwauzs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhftporo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtdxtlagwe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gthkkedmnm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtjfeleqat.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwnnxdbvh.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtxauqmogl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtafmoquyy.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtdaucggbp.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtiowtgydj.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtexnxdlxc.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtizcbytlw.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtcbtggwdq.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gteoqefjas.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gthcgetude.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtbrbeskaf.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtmjjgsyfu.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtzzncprmi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtcyhetmkp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmnmtmsnu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmqrewhzj.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtptdekehg.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtrafrpxio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkdfudji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtaoxaqodk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtxgcwoqrt.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtpjefpbwi.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtzgcvauoa.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtbxppouac.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtwiccsrdt.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtrzkewqpr.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtewnuyomz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtakuazlcr.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtknziokxe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpzgakeb.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtzxtcipwb.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbbfasys.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtopaiwjnb.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtgcwlrdne.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtbrkwwrhs.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtcgvcjxlj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtdrpqrwje.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtzomkghbj.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtnizucpmp.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtuxfbsyfm.html


<!-- 参考信息 -->