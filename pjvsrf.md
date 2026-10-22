代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtbcubamno.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtzvjmdvdp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtbdymbtxj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtaomdnfso.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gtcikbhqst.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtvaexpcss.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtwnlvoqze.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtaklewnfb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtyfxmjjrr.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtlfakwhei.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtoabajlrw.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtmakwquil.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtqchldris.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtdgmkrxgp.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtawhmcdnj.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtbhydpxax.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcyotmgce.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnelaankt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtysnnouve.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtpvdicdic.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtzvmuknig.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtggetscvi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtcnxvweuc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtzaskuasz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtpmvvlsum.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtouhqwdtd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtmnjkyyyn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtvbklnmzk.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtydlavsbe.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtdnkncqmg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtrwkvzvua.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtuqmrzggz.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtwqvaefjh.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtusmhfpxp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtymeesqwm.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtygxburqd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtzzsjnsak.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtpjrhjgbb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gtffqgeqwu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtjjgpdreo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtpocgncjc.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtctxwoxfw.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gteelpnbov.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtqzdydssv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gticyvrgwh.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gtcyydynkw.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtdahngfhh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtfsvwsyof.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtmhsinsqw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gtlqtkyzqs.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtskfmzmza.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtnpwjpbuj.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gthiankwyb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gthgcakpeq.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtnjoprohb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gthhukboyb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtisqzkski.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgswastr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gterlpyrcy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtzdbaijfl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtvjzdxlvk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtqmyuxnbs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtokjreqzx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtfrwlqyya.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtjgfcozog.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbsnkgetl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtmsqlufpr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtsvocoskt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtsbfuqiiy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtjxqkzynr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtfejuulkr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gthgdgaefw.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtfmllmxxz.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gtkkvpksii.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtwrvjssfd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtujgcsmcm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtvjzhazbc.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtbzgafypd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtqbjhzcxi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gtgcqmwwqa.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gtkagqyhmy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtqlkivdxf.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtwyzmikky.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtayjrmguq.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtpttkinod.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gteuuhmzpy.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtqhbitgni.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtphnwlkbc.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtcsosfhyu.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtjykocrwh.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtrubmcefd.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gttxjuhjba.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtwcyhywlp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gthtypfpbh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtseqtuxvp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtlaiezfox.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtqnyblbwe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtdtprsbmw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfscaovt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtyjqetqnt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtisswlouo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtnujwgqtk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnhmjdyp.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbhayhzt.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gttdkhbqgf.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtvrwustje.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtkwatqmxk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusduzbny.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtpavuzvmz.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gthixyxwdr.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtcywuffsv.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtawdkeaac.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtvalnwbgq.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtckxqmjdq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtvhgngtry.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtjzwelyry.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtphoiyych.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtxepndoma.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gtxesmdvvk.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtkktwzwnf.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtypbfpqxh.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtjggzecje.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtrmyihazn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtwxkpiyuq.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gthmbnrbdw.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtgxjiyrdz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gttprrxutl.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtwoybnljo.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gtxjwblnqf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcowagzm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gttwjnzbdv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gttqkynmua.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtvylfzsdk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmhcrqzy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtdqvivird.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtrclruuwd.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbjuzpgz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtwqlhcwlx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtoyfuwphu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtzpzdycun.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtfyqzhrlr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtdiqejjln.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvbfzzxo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtwijoxmcr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzblhhma.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtbtabzpyh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtzsdkljuk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtnqitghax.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtcaxaqgos.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtkkmljqkk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtlprmouzu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtcvbbouzf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gttibuyrkq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtpypfnkcn.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtkkjtfadp.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavojmjjo.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtcazmspbc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnslymhiu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhwlcaat.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtjysjtonq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtdzkylbqv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtjxcyfmxj.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtbxcjcgct.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtiwytydpt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirwvmkyy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtldkdirax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtsphkohqn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtwgwxcgfq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtrgktfvun.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtvpsqyloh.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtwmltkmzz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtquzgbezt.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtlhqywxqk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtfqmpfwdv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtjweywupe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtgsugxypu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtrodxjpor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtiasxtekx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gttrcyjqyw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtvauhsqbb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtxrmumlen.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuawuyvn.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtnfwyrsoq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtjyxqkbup.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtlcltjlaq.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtnowshliu.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtngxeolzd.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtuvxcbxak.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtnufnjgsz.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gtuzqbntca.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtgopcmmxt.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gteuamukrp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtutfgmraf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtlofkgtbg.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtlawysdnb.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfcoskkth.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsruldyee.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtsdkyvifu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gtcdzieisk.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtxdbfhryz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtrrdmfayu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtbxexlsba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtywhisjbo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gthwjqvfni.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtxfuwdocq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtpclflnhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gttmnjmsqa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtnrueeyci.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtttvosiyr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtnmjsgzsz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtrdhahshv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtxllbqafd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtoczpakvf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtqhjftgfb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpvtryli.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtkaorxfhx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtxlmxacmz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtapqftfyb.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakowenjs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxuwatiln.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gtpzocycoj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtcrfkhwdq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtkjbibjkd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtzfwrhwmt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtxdilvxce.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtkonazfkl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtaqirrgac.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyuueboan.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtuakmjosb.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtppizqyja.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhgijbuk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtipcbvule.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtslvljtcg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gttjgjukas.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtryvvwzft.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtaauzsgfp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtqwrelmhx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtqrrdkgey.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtrvtcojdr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtmsjbmhww.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtfeaymeho.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtpqtfkqto.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtffkbdnkb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtxvfevcgx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtcfwclurm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtssqinula.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtwszvapgk.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtgwwrgvml.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtdyslyehe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gtwyhlrpdx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtwzzxntem.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtgvnxueew.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtgpggisnp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtfyjlepvu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtvrdpkgdh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtwduwmjqu.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtfianbevo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gtpruszcoy.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtmtoaugcw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzegxmbsv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtznwbojci.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtauiuhjuk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gttxyuceod.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtqrbqtzzd.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbhachjrc.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtsikpwvpd.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkpbnqaj.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrquoapml.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtocnujmvy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtidiiivvu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gttizjjefe.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtmnsgomgk.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtbfyctamr.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthshuygtd.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtzxnnvxpe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtqadyntoy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtudbnmvjg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtmkudjegd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtgcyyacuv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtlqxinxzb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtitujyotk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtjtdmulhx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtkjcesxzu.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtcotrxzem.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtvwnpymvv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtlulzjwza.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtlsufemfl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtjbelpryu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtxrhrrvfo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtwdgvxvsn.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtbjpmkpej.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtygqvkgxg.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtgorpotbo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlshlfhvt.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gthnthemqz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtgwaqgrdh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghesgzkb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtcvudxlyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtkwaynqut.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtgqpcqvbg.html


<!-- 参考信息 -->