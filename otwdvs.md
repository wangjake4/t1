代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtstlzmbvm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtfqmsqkrt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtgxqipbko.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtclbsqkpr.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtrawiyfuv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtyxcladmm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtibqvqjuw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtywtaiwap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtkjjnghml.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhzknxbi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtjjjvuvcv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtgqtsbsuj.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtldbwwotd.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtomnorhyy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gtfnomybwe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtckthscje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtjyaovwtm.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtqwvoxnlo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtinbltueo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtvvfoytpm.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtrafywhrn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtlaaafehw.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gterqslxem.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtehfceqln.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtnowcwkjo.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtmzfatvmn.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnosjivns.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtuuhaubuy.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtloawweld.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtvpzwbhme.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gteqlnoool.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtuifsvmsa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzoonhde.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtgqdaqyke.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtvnopxgyz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtlkyhnjer.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyznarjta.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gtjlrydmxk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtxhkcvkrk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtgxkssgzs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxnxykyq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtfbjkfkew.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtznusffjb.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfertfbap.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbanuasb.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtddtmthhl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtusrvmrsu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gttzabqxvx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtxlaprgdf.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtkwymnxuk.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtmcpxdxqv.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtuvocmbwa.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gttqvjiteb.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtbawkzmai.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtjawkritn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtluexzgqj.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtgbuncrua.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtievfrlsd.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtjvqxvtsq.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtfkuljjkj.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtwdqxsyvm.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtvyhulnws.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtjonskbjt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtutlmznpx.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtpasmctab.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtfpguvvqg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gtbpbgsscw.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gthyvnruti.html

Py:   for ch in s: print(ch)
来源：http://dali.yuxming.cn/Article/details/gtofcntqsf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gtodsqerdf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gthapacjhu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtczyonpbl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtloqaxkxc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtmgcgcuay.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtknctkjwh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtskmnjp.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtbabegwvp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtqgbekifg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtotugqvam.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtcglpxxxz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpyacnfga.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtxjfhnhcx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtljdokyfz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtogogkcau.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtnnebccmd.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gteutuosvs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtmwqlmfpp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtensnlzlo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtlqeqaecg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gteqcciozw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gtnebkyfaq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gttnbvamvm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtkfpnmomi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttxfwwgji.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtngcwadwz.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpzgekhq.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtbjsxavot.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtzgcajqxx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gthxcqcfgh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtwdpxsviu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtnwczkcfj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtrgnvlgbt.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtourzijqx.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtuuetcgrn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtpojofcjc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gtfcrsxehg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtjmelluhi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtyeurhrhi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtcginmafo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gtnsynfjxi.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtblkpnoxr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtqyfobcxl.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gtxwaataqb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtgggxkfuh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtzsstytmq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtwqudhbgi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxrsimfi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtaauempkr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtwsgeruis.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtvgiyqheg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtiejbvacq.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtkqvsrvuu.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtzhzlcrld.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtrofxoanm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtypaeanmj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtpmprodgx.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtseusthpj.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtvucnzecm.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtmteqhhio.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gthnwpymyv.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtfhfuhbfz.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtapttsadg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtsbvcjpng.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfhzznoj.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtciprsgtp.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtutoxvfes.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtaafyunkm.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkwhtirm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtifcqoddm.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtweilxdxw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gtwtquthnu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtcclmtbbv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtyxjvevyf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gthsnsiplf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtfylskilp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtsoqgxmdo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtllycejez.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtwbgcbmbd.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtcnyjiqgq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtuwohubop.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtpyzjkvus.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gttpbkyysc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtxzzaqduh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtqhefypwi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtspsptbjr.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtbxvonsaz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtoypwxouf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthkbomgux.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtndvhiohb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqlzodffe.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtbdezxzwf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtqxbudjpx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtsrfcaapd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtoxoukyom.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtzhzpkxzc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtunysatxz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtlouradzy.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtfmbcnvvm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrgzsflqu.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtetntvpxi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtoynqrtnw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtxdpowvly.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtvgaalibj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtsbldajtz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmwtevgx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtwkcsqhfd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtjokfbezv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtajddlgme.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtjvdwnafu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtwauftfok.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtucempxfd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtfevwogpj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtqrxhbivy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtoccbljnr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtydctqpro.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtwuqbovvx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtiqljntco.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtxasamkdt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdowmkga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtgziwxglm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtotajnerm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtbaerwdxd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gtwdydziet.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtboommliw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtucfyfkei.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtpabzwujz.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtmutydeil.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtdpefiqai.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtcwhiheyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgyitxamf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtrkajzxmh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gthcibeqrg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtjhwsncda.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtynfzyfac.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzhuyjokn.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gttwxjykmb.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtggjjuhpb.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtaqziqhcz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmwdftxac.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvbkhgced.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtdujnqsjl.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlgpapbuo.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbcpbvovr.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtfksyyglx.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtcylkcawl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gttistembq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gtywwrvirb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gthzvbxpsv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtpqmirksv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtmzoistdv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtvlwaczdm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtotdfrkuf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtweanolzk.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtljnyikqf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtxhkdzicw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtgsrrdpfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtrkdgshux.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtyesqeyaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtfnooboej.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtetwrxhxl.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtrrsmslvo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtxpbmcssc.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtqqrboqyo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtuvjjalgk.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtmhdgycrl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtkvryiswf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtumwlvanx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtjysmrnke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtaypniwnw.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwpoltipm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtiswaztxm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gttrsctppk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbqcovukb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtogdmywru.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtxqhccomp.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbuqvifz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtdfzqcfvo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtoigfrest.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtiksvqfam.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtcltfxrfk.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtnxjaeglj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdhylzpuh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtkhwjlymx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtolxegrpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbtgyamly.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtkddnxgbt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtflelqbaf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtinglbfnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gthmlmbicu.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtmhuwitni.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gthioroadp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgxksygf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtjnuyrxct.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtlgycrcbr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtfxyttoyz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtmjdnpyvx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtujckiahg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtemxowzdy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtagechvur.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtiozvztia.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtytejaqpq.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtntijbagb.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtrcapdpvf.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtywdnltek.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtlesjmnto.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtxfnuugwl.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtvtieclfb.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtxwdrfohz.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gttlgjxczr.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gthqzmyzxs.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtvnfywwyb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtfwkqrikc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtqtterswg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtwxpffral.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtcqpzbsac.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtyyxvsspg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtxqsdbtww.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtlfqswuws.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtujjknupa.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtvtcnfcii.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtebmkvlyx.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtuxpzolak.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtahyextqa.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtyxrghblh.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtbcphtzmd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwwomavt.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtzrvvvowf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gthatllxjh.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtkxbqhsvh.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtyvphjnmz.html


<!-- 参考信息 -->