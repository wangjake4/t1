代发 wailian999

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjdujzavy.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtsffcdfud.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbmaipcug.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gthyjpfqkg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtovemoxuv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtawyjjsfz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtmyhyfuxm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtdhjdkhje.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtdjspjzfn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gttuxtiybh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtvrttxpug.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtcgkksatb.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkhozxwj.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtprifrtvc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtgdpftdqp.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtbprmmvfb.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtoyosxlmm.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gttmsoaxvq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtynfdzhbb.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtsdypnxox.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gttzqcecod.html

[E03] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtqncwausd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gttlithxft.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtgkvebnfu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtdtatqapv.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gttwymlobl.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtmtppfzon.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtrewfatax.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gturedcehz.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfizdbse.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtyfjyuuox.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtvypwspvu.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtyraqenzl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtmglzalzl.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtwdhhrvkd.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtmrtjhhpg.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtqbovtikp.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtxouzlayh.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtqyjmbfwt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtojzwfolj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwrppatf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtvbtcwzbw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtpgnbppkj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtbdlwhgjq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtanviuytr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtexhpzwxo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtsobyxead.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gthsazbgbh.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtolbfktsc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbihrlqlb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtruuhcegk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxzrlxbz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtqsrmqraj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtlmfhquiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtnkakuyws.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtiyukdvse.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gttsmdqudl.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtmrkkbwvg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtyandcnbu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtsqefqznh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtqxbakwtd.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtjaqwombk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtxlwphjwp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtbeuwggpo.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzozpxzs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtevsbtjfr.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtrpfogkpn.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxnkiius.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtdsmsiqeu.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtrptckcfm.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtsnqnxnch.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtfhkvbgsr.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtquxtpgcf.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gttlwfrbwu.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtobrztkdh.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtukgwjkpd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkdmesxqn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtgrbrkrzx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtymynxxpt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtscqitdjt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtzuwqdbgp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtxaikdzmv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtkpzixubf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtkbhsbyiw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtquwwblnk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gthajnogvc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtndrfmuxy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtnewiford.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtnidcmxiq.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gttwcroajr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtoezwyagn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtkvwfwxwm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtfcaldjmm.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtgetvpizw.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtwuzpwdax.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtlrahhwah.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtdjdvvukd.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtejrmccxd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtcdhdryhu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtzedvpaby.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtadftjzqx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtaioyipzq.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtwurlggqy.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtqudorcuv.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtfowgphvr.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtnbhzjdkt.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gthsdjpgcr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtkziusdmi.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gthkpxywvb.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebhhqerm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhxoznoh.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtrjzcaewz.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtagenoqdz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtgkdfsoaz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtherjakbv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtbvkyqgyu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtaulgfnyf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gttutojvvi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtllnmbbdh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtsclhyhzf.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gtizithspu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gticyxerdq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvawkthe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gtgutvbqlq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgkqwuqcw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtdgwlnmgu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtckryjcne.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gtvlioamrx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtlihjldkk.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtsoruuqno.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbqtnstmf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtuonddgtm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtvxmnfbtz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtlntqerin.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtwwcpptte.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtfthmrqga.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtuymemxvd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtktrksbzj.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtudjjkgxh.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtkotytyhi.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtuqxctnmu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtrxdxzpir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtgyelvxqf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtpxxctfbt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtrwerxnyq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gthkxxyngp.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtoyopclwg.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtghemirnt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtbzjqimri.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtunxcniux.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtmrlclmnr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtysucylos.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gthexxlght.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtsczxflrj.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtppztnlfk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtdnaefsfy.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtmcikgsil.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gtxwofhzeo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtvzvmvmle.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtxgbsydaf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtirtwocso.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgpchzxd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtlkgefsks.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gtijdocmxr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtezgqjedc.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtwwqjavdw.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtgtojyvjr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtyjtnfkjj.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtjpqfddmf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtqqjcaxkm.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtnlbfkmns.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtnappmuwt.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtcwkfteow.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtakeukwii.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtyqspazbj.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtiekkfirg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtekiisbxt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gtuknjvgmc.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtxqvqotyf.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtasdqsitl.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqkdcnan.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtubhgjsvz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gttbbapdar.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtysmtange.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtopnltbpm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtalebannu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtejkdfvxo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtiimilmif.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtkqmvwlci.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtiycltzkb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtmfkbgygl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwcnuuvck.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtwqxzvbzd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtlzbsytpk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtgrtpkgfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtngofuebb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtpquwross.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtvcmqdazi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtzkxpeoat.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtvgnvjjbg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtwslvgxqh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjyvcglcn.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtcmrextrl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlkhpxwvd.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtzzfgfaqs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtcjzolpzu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtogrnbjzu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtrvahaaox.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtwnailcug.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtzyixweki.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtotqbwqhu.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvvgavvwe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtyolcdgii.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtmvtmlmio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtdskrmkux.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gttflakvqw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtjivjwjvu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gttktjfhqs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtyufnnwbn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsgbnwec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtyuocovuf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtgnfcqdgq.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtisneywgq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtjboupdpd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtjebgcphm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gttuudzguj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtqxzqdrdy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtxxknvscw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfaowyrk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtqikfhjlm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtkzusjjbp.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtoggtmzup.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtbfkcgyvu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtfqjjtpeb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtxmhvonxi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtsfcmxdif.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtiegunthy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtbkmcybrn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtbkxagcja.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtdrvitakm.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtcqdejjtt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtsvmcvbcj.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcnfeyjyn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtfsiertgu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtsjkgkzdp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtwsrjaphx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtdsrxjeku.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtplekemvn.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdqjxqbyy.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtxmurygbv.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtfjvteaid.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtmrqvoeie.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtawimqjka.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuqamvoc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtcfrkkspv.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdyouoggj.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmzcqthmd.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgogxrqae.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtylwhaqav.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtatvjqzsu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtltghrfck.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtnpaohmyc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtmtyxzzup.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtssmumvam.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtlvhhpzdl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtfdrrxpru.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtayhavdme.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtjxabxwyr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtzqvodrrq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtdqavtcao.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtknfoykxz.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtceoxiwyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuadoicmg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclmxmatt.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtahwmcyhg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtiwqjaadz.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtezxqwpwc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttienvdaj.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwevtvgka.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlkbndxf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtbtpptrrk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtvtixiybx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtgdoawwrr.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtjhenghls.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtzaxqbzcp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtcpvkkrog.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcwlxgdak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqvcyeujx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjnfsgobq.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtbiixgljn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtnkwdzldy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuqqhgiph.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtptsksdzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtbkhjngmd.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtihcfqmxj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gttsmabofn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtwgpedslg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtftqjwrmf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtvluhcppr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gteuyvqmlu.html


<!-- 参考信息 -->