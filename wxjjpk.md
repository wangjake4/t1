代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gt2clmejevj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gt2bqsdbnql.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tktiivbr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gt2qboleyoq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2sjqggmtj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gt2wfmupzlb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2wiaywiuw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2espfroyy.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gt2ucjoyxqt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2gxhgozqo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gt2iiieqedp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2aemkapim.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2xnerxjxw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2vpdryhdf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgbthntr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2colxmaqg.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2bwjsyeyp.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2bhtncnlg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2ixrwazjn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2sdhbkmlf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gt2urzfshqh.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzhvqnnz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gt2sfeavdvj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zskqvczr.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2oaserukp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gt2hsfqbvyk.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gt2wwwtcesv.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gt2oqakithg.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gt2vwrlddji.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2alypznta.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2bolgffna.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2mrjcohgc.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpuatdxk.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2ljjalabl.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcgdzqvp.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gt2atrocmpq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emfncwch.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnegrtjn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2xtpgsheo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2kzitegje.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjyiieql.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2amphjofl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2kcwckgwt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2aanspime.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2xngcohsg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2fmmarzfx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2gxthnwqr.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2luvrqkbr.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2kprbyddg.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2tpjhainr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibemltke.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2bjynemnz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2peijzuhj.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gt2qjenuxnk.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2aeovjvra.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2qhghnvfj.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2txqlfput.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2ofbujpwo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2jyhwesxq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2iaeisjjb.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2pjwrerak.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2zuujkxdi.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqimtqth.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2uglpihsm.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gt2eeyqyfds.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2hnjgomwb.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2giwzlbsv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2sqyffgkn.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gt2zvnpiwym.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pisrgahk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gt2twyqciws.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwglnock.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2tctogopu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2mnrdrseh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwvqhcxi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2tixelqcb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2drxrovtx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gt2cpvgncfj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gt2jszjazzg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azspafsr.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gt2ylhplxbd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2nifuzers.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gt2jkyoyxlc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2cpnfuakg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2lyjlvapt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2rhzltqnd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gt2ffncziuh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gt2hdfldwuy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gt2enkybzop.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gt2edlahnca.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gt2wxeugssk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2txvyklaw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gt2eafdokje.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elkudssp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gt2pbqwqmta.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2npztqkkp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2nflgzevh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2pbzmpbib.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2yhcxswcr.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtwuytc.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2rxuubzcr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2gfemipsf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2axyxassk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2fyyxrqsi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2mkhsvnwg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2ezabjisg.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2cpbipdgb.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waxgcglx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2mgqzuiqf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2xembhdqb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2idynehiu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2sacfdpem.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2qbzvntih.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfabdjoe.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsyhzixr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gt2brtmxbot.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gt2alqgliwg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gt2kanalayt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2unwdtrqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2ccniksjy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2crqocniz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebtsjlya.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2ostnlbpw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2xrtazfaq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gt2trqjflaj.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gt2yhpwtiud.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2oktniffx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbdnfbey.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2qvdzwjwa.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2nuaztsxv.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qewzjvsl.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2bszvmefd.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drlnhimi.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gt2yjmulvra.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gt2xpyazknu.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gt2ekdxfhim.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gt2dppbrsxr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2udsdtusa.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2grnlqxrn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rnbbajkd.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2bokzghlx.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2ojsdsoxt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmvjobes.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gt2doxojctw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdspijf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2uguvkbmc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2ymqvmzbx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olwandlu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2rluqqbzj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gt2rojinruj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2cltctfyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2pgvucmdt.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gt2xxfrkzzy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gt2phgotlvn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2ievdkxdo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2jmdfgjws.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2tojqbqfq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2bvkrsxfb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2zjgbuhod.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2nuwrguxd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2mdommaye.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vljjnkhu.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gt2ohrydsxe.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmovbrzj.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gt2lsiiwjwf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2jaqlqrlx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aehnobmh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2clfsakgb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2ymqgyubm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2vofwwaml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuavsdi.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2bpravobf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2hopiabkp.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2xwggwgdu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2qrhhslts.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fdywpdrl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2usfafzzr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nksmdmpi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2muzzkujz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gt2juywkesj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gt2ervzdxnf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2lrqezvne.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhgebjpv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gt2hnhpaiqe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsamdspe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2lhegcrav.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuzgdzvz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2ttktrhdw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gt2yxwzmbvn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gt2stvuhbwo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2edtuzryk.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gt2xvfvubnu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2htwoinzj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gt2delchwty.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2bvxwaejg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2eacunfzl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2drhralgv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2vckxspaw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2kfmntyef.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2ozzrelbq.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2legcptlu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2rtecfzmf.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2nopbrfde.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2wqqahvpr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lvjcvqpx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2jqvtpuvh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2rtwmxofb.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wzctbsgd.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kfwnvaim.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2exgsrlxt.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ydnlfrzo.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2htrkgzrd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2rbuxjtkb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2oaroqdnq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2uemntcfl.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ynymmnoy.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqtxaqqn.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2ondcxmur.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gt2ltifeedv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2iahwevxj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2akeinhxv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2ktpqdadi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2rlautyto.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2hljuuooe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2ypuosjuc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2oiiekcgv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2ireziaip.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2zeuscuec.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gt2aorigbxb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpegyonm.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2gpouweau.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2jsvyvqzm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2oaecamre.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2lxiyzgll.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulabzrmd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2fhobcemc.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2bywiqjpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2miuudcoa.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2jnpcpxvc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2uzmmhmtq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2yfcmbide.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2wtjwuhij.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gt2uvfdynqj.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dzhwvkax.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohsjtkyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gt2cnzcqsiv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsiyhicg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2qriuzihj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2mtxkphst.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2daeilfvt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2tbzipsni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ivxsmmip.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2uqevalho.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2sveuabnz.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gt2rvixvunq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjhvboym.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wamebtrh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xvtlcudo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2gqrespqc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2treljepu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2udxcymvh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2iqlraleu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gt2iexuzcca.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2fjauknin.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2juqjqdsw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gt2vxfxzlfs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gt2bkntkkep.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2ilralhea.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gt2orbrkwku.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2qmeavufc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gt2gsqrriuu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2mjahccbz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nuqxpuwo.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gt2wsgsxoux.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lqbyyvpw.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2fvccitlh.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grscoxty.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2krunbuup.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vareyqbb.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gt2nszmvbfj.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2ybljbses.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2tkgtvinx.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2xcssbuxl.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dsckcjib.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qnvtduhp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwcxvwux.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hntvluwl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2sitgwuwk.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2pqfrzdbf.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fdksgtjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gt2bmclxpdy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2bqxiajao.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxmhecpt.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2wycnjqxl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqskho.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2cqiuydfj.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfqxnkqa.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2cxnbydxw.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2zvabqdts.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gt2ovvavfrn.html


<!-- 参考信息 -->