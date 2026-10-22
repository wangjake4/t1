代发 wailian999

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtknjpgxkb.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtceporobp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxidkdulz.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtcgyhzcay.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtllcpjnfv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gteekzgzdw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtxvtfnvbo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtupdthxwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gtjcstuahr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gttuumlmou.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtcacxvkyy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhnbtiky.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtmuzemtxh.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtxqnlsbxi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtocbpjlop.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtprarahhl.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtjndjdoju.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtpjtpbtzk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtorxhrcdg.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtoedavhay.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtchuryofs.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtmadwrxhr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtjhihskrf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznaiytts.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtrggrkgbc.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtrsshzgrw.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gteuqxipof.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtanaxhecx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtzchevtep.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gttyazexlf.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gtzrjwtlzo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtkvsfnwkq.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gtjgcefbpc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtdyqmzzcw.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtdyrrthzc.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtrbhatjia.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtufcsatkm.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtkzikvxsx.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtvbtzgdws.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtltcjoidy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtkvyekjxb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtaqshsyqt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtomsuqhzs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnohadqcn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtckrmgsjl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtnptzkpuk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtuwufeiup.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkshxjuyn.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtzqmydqqc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtuxpdycss.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcyxhadgc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtamzrjwso.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtqyounsfb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtmytzgdcx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtwnsilpab.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtwxyzlimn.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtgcywmvmk.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtsngnvyqe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtlzikjump.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtvtibiypp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtrpwaboqw.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvojghoe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtjtbjdbjo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtlvdgpetk.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtwzcswxoh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtvhyibjoy.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtpxpoyhgw.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gtdapluwkb.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzvjxgvq.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtmpwhlnaf.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtdlksgevq.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtirenooos.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtphrbmbiw.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtkfxfqflb.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtgjatrbbr.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gttphfelqm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdukubiws.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtxvuajzvl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtikqpklot.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtfpvixwtj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtskmclqks.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtzmffvqot.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gtbhysvcmk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtxkrmqrlm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtmapbsbnt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gttvzqzfds.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtlofwwvwn.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtpbibqzni.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gthbcwofjx.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtizzmpqrj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtepqhkpfh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtmnybcngb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtpomqglva.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtprbdzjil.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtzexvuqcw.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtnytrxwgv.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtdnppcvoc.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtcgxdrjfe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtbthxkdix.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtjgumwwnq.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtbyhjtvih.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtqboemjzk.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtpwsqebjt.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtwublgvxl.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtwbcudmpa.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtbduigsyc.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtduoqhyyr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtumfteafd.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtciwcttkr.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtrmjxnbkv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtoexaiaeh.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtfvxzplkw.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhzyowsf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnortsfgg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtyhlwhpis.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtxzxezyer.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtywzymxqo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtxgvrtxis.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtjyqfymjg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcvnhysq.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gtygvfjgsl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvyvbumt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtgfjmnxga.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtiqzatboi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gthlbrgryv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtqcufjaeq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtdvldsqlh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtqvafsbbm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtwqjhldfh.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtpzhqljky.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gtepbgkfwv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gttkjqivje.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtubtkxaix.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtbsujbqyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtayywyury.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtruhxhupm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtmqzprjbk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvxgbjgs.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtoekhvnpd.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtofrovufu.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtryrpgfmt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtrvhudreb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtxduavzet.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtnorammaq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtjwbuvkmf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtvufdkyxd.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtxpbmlxrp.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtzpalkduk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtcigonqcm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtmjzsvfql.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtryobvkpf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtxvgshfrm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtnvoaurmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gttoplthjj.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtuybfyryy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtnjjhdfko.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtgjcojchl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtqcrjgytl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtqeckdknj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtpatfbhbq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtnxhgvrib.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqawlpej.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtdzwnvgns.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtwpmuxeto.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtszhmyqvj.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtihzlzvfn.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtccnigwkt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmurzfdie.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtuhknmemw.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtewdlnyvv.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gthrjmxlhw.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtarcsjxnn.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtlwxecwmh.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtattroylx.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizskmyus.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtrgsvrzze.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtdvnwttue.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtcruhrqjt.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtylkolplg.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtadljvhfg.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtefyojzua.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtaunqzmat.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxyvzkiif.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtyujdjaew.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtifoaeupl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtytdkghec.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtqaeqlngc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtyclwnmsz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtfivfslpv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtyzudenvs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtzbbrhyni.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtwcdufmvp.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtvzgenkvz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtoxqoddkz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtzodcewgo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtyoimssjl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtmwnqehib.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtiszhdnzd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtzfmgrtvo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtblwpktzk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtukrbdzuj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtudweqeoh.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtaotmnhhp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyzadhzql.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtxskquhhc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtgvdzdwge.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtgbitouyw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtbtfbkxig.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtsbmhvkhf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtgonjdvqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtzxrxgdtz.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttpmpnsrj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtdetmfman.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtlgcggyvq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtqhhvemed.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtfqpvqhsu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtiyygndje.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtmmraxnsi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtxtityfbv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtgoqdcuzi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtjjcnbnpg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtgkiswvjm.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtmkmgomfm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtzorbqeia.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtizhxevfn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtqwmtgybi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtzctyngtq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtyaobhmew.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gteneaewqb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtalhgojkt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtfifvpytb.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gthehmvzwu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtqbljlwjc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtsiqnbvoa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gthjlijiir.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gttruoidvm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtasfnlcow.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtouckoftx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtjqsrjrqu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gttzkvapxi.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtvwtvtvuz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtplbdbfhd.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtimdyatmf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtiwjcyofd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkkjgmkhh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtxydhpbua.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtwquohoow.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttddnawxi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdyotnyjg.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gthsylzrqw.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtzmgfbjkz.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gtpcrbbhhk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtyzgbzdsb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjrqeyxmr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtkcpadtlj.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthjrquhmw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvyljrwtj.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtrxftcuap.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtynyykkis.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gthopffluh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtxqzeoyqh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtgynqothh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtfkbpighd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtshvjcfte.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtbzhjbqrz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtafvirkbj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtkpyyqrsp.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtsknsaslv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtphzyocbu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtksqthkne.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtesbnunrw.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtjlcoqdhm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtopgqqwye.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtvlyjfksu.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaskoyvae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtvwwiptmq.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtqshfbtyf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdgtjkbpv.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnxheuupj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtyleyxbhh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtybnouung.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemvhqxag.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtfntponuc.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthpdbhcbs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuuocyke.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtkmecflgl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkprveahn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtoyvcxsqa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxfhsusvf.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsuqajveg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryogedtu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrjhhcmuz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyihjmqzu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxtxopzwm.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gttoxajcnr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtoisujmfv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtftxnrhbt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtgjwzwecx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtjrncfdev.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtoyzjtrhc.html


<!-- 参考信息 -->