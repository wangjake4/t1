代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjybfdio.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgqlmpsh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2camotrry.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2qeymclzt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sggazrif.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2ebhmekyq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gt2xowfidlw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2kwfqdumv.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gt2pykbpqmd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2aeypohqq.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2orrgdvgu.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gt2baddnitq.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aotvylze.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2rugzpqhs.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2txdwyysj.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmdktwpp.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gt2gtosncje.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2zsloufmu.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2nhaxjjbz.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gt2czfgubry.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gt2stlyabar.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2iytuwiah.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2manpmtvz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2grdfzgxb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2mhdspqsi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gt2acstsiku.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gt2namcvslz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gt2rfmqwvoo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gt2yiflymsk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsbzqtsf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2axvskeed.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2tffhoazt.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2tnmoeaqc.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2ypmlycdr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2ibmxrixt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2ffknoukc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzaeqyun.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gt2ufhjbftc.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2pmratvnq.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkuyannh.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayjmetnb.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2rcqbffsd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2syynrbkz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2mfivaync.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2qtjycknm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2bbslfwei.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2klskahzz.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2vkcxttyw.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gt2cmrhmqhy.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2psteuoap.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2snpwwasr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2kplyeljm.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2ouqhwrrq.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2gzasjyvq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gt2swiuxyqs.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofgcifsf.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyxguysn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwvbhomu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2spjsyurt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2beccgkyr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2usmnvawd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gt2txdixrjf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gt2umuroaxc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2ltwowhdi.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gt2vhunaehe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2rceoadny.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2dnrmrzcy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpydbnqz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gt2nlfxehke.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2eoragjji.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsqhcndp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gt2phrjwtdj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2luttromp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gt2ztrtoisg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2dwttvghe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gt2pmniivoh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2llnhecfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gt2rxyljcun.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gt2rzlvczxr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2xfypttxi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gt2mdnipaov.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2vcaocwyd.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2luuqyyng.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2imanzxit.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2mqojizbx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2qpscwwst.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2jyltownw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olvzglqv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gt2qdjcokas.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2drjjodxt.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gt2dyaxszgk.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gt2xgiwvdaj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gt2wldielwu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gt2lqddjuuz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2mxreqjlc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2axlmbmfh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ltenwlve.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2lwuymkob.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2itiodmvl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gt2xhdcdtgn.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2nizfrydt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2eegxnaqj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gt2xiyqktmz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2jytstjqt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2aaqyzuxw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2osjazhma.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2xalfgswu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2tgsuxvvj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2unlhpxls.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gt2gqffpqkg.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gt2kumbcnyw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2vvbuxbnu.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2hxvnxoar.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmkaeuog.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gt2xsykyans.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2nnbfmmfc.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gt2wiwpfzjn.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imvxyvqu.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2mmahhxgd.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gt2mgwrkije.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gt2dqcjpgsn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhlyikaw.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqgwrkgl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2dndntgxx.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gt2vgpquoey.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gt2jxevwvts.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2etxbkmor.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gt2nhegdwpn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gt2gkcrxgzc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blvtrvqx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2juzbhxcm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2eibvwdhq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2ukrauxpj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2gcpstndw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2bxwpspzh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2mlixgrcu.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gt2ejlpdxpz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2unrecyia.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ocjpjxwx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2navtvqdy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2mvhevdto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2opnkzrmi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gt2tjetupos.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2rdzsyezi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2gctffbdf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mglbppai.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2bltqwfyd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kztmqiij.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ausufuqv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwivsnqv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2jkorzvzu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gt2jaeettal.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dncilhyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2hecnoeph.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2mvixbwne.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ycaeiamf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2uieatlge.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2cjreqdgp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gt2rpmoidxd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2zuvkkfus.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2gvtdfeoz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2uhsqdokp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2jqztjaqj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gt2jddoqfqp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gt2klpszbeh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwugsiyl.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gt2imgigdhu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gt2lzolcmzw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2wcnchsng.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2mgnlujxk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2zzwliloe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnztrbyc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gt2ntmsbcpl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2utyogdiu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2wtzegamt.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2jxkjzppw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2bnkzmftw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2peoxwrsb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2nhxoleis.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2tjsykfyz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2aqeqirad.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2qwbcxtqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2npdfpudn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2dnbfwxjk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2czjzvvwg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2zsjqrics.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2rlsebzlt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hixybobq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2didtxagz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnzvncwm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2arqmpcio.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hnioyiny.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2gulmorag.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gt2nrwtvzse.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2wkmpigeh.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2dfubyoox.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2yhzaqtpl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzfogpzu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2mihuzlrv.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2urwaadfb.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mzhilvzg.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2odifwwpn.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2tlpzmedt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2yzlgunpf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gt2egzbljky.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2rvimyddk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2uivjtfil.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gt2qpjhvvyu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gt2mzjxogbc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iirqnfbd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2uzjpjewm.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gt2oxbqzxmn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gt2efrtudvw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gt2fpjtctds.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2lfsapebz.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2wwumxint.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2nnurqapr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2lnfshzlo.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2odsexqcp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2kpkbszsa.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2gsdenibr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2emjjutnm.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2zakytcbr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2jqkukrtu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2sruzdsjc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2wzvpoqzw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gt2cdhnggof.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mglkuhjs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gt2nwklrvfk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gt2mbfwtefd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fekgbgnr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2sjunoeeh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2arnigfkw.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2lwtuxbde.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gt2eziuctkz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2quyuifxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2shpzyicw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2zpbxegqm.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2ldrdwtsz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtfwlicu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gt2uljhylbm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2fumbjivy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aokjugtw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2szhgbfbw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2uoqswbsw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2bbkviysv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2wptbksbo.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gt2cdnwmzuo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gt2wrwgidgd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2dlenxgfd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2pdpqrwej.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syhpzglx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2vyoedovb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2xevpqmrp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2rrcyuzbq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nicwpcgf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vxycrfxf.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2yfptnawj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ricoedfp.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2nqfdoscp.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2qxzmitef.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2zqcelmkg.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2kyhuvjen.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ujktcstg.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2nbmgbuqc.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2apqqcofz.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odixzcre.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgfvglfq.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2srladnhr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gt2ogmzhdyr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ctoeyjly.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2xrxctaau.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2pfrydmuq.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2gjdbmqln.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gt2eslddudy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2kjujwoie.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgkkyfwv.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2vxnipmdo.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gt2vfpyptoi.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2bshoczdm.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2wxhuztoy.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2zphnrscs.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gt2izimleac.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fldalrru.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2ssqdqviv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2gepixthz.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gt2trsrdsdt.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2ulxwggtu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2tpxpqbot.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2gptyxzae.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2efoxtolc.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2gumddbic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2nvaaxlkq.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shjxwnxm.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2egasixbg.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gt2jxximeel.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2rjkqzzle.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2mgerkwyq.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2fpvfiiwi.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2sczyhyzp.html


<!-- 参考信息 -->