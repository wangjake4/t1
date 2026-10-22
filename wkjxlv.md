代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gthygmhdsk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphdykgvt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtdrnqldos.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtwemrffib.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gtjybiqfox.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtsznmrwqy.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtbossrtpx.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtuubsevum.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtalkmecrh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtrixjmvmj.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtmdofkpgj.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtfrcoyhfq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwnlfakt.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gtktcdhsia.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlhvpqtfs.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtlapbdwsf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtcimovfhm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtmpzgykfu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gthyaudaty.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtohjaaxgf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtczyzpwtk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtupovxndm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtnalxfbfy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtdvhrpjnf.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtqnvlefeq.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtanxzwzjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtuknyddqd.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtqhntzbdl.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtcvnayukh.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gttcyafjku.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtquqaarod.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmacbsebu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtxoqzfegu.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtpkvllnfe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtilflwfum.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtqsbmoqzh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtpwrfuwzp.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnewgwzib.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtywgozwsk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtewagsejw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtnsxawsmp.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtpwscjawv.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtokakjkko.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtsdivhgzq.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtdulvmxgv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtkrmdbgzv.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtwjrqimor.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbohfpqm.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtzaaqzjdy.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtlmwljbsv.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtwfnlztno.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtfhpldvql.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtfltuaobw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtyacvsqty.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtzsnyyewx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gtjglsuauw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtkgomgqwm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gtuwrufwvb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gthivlszhn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtwzfiyvrj.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gttenrxfgn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gttioumbbv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtwtozgijd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkszfegff.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtgizseupf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtozjvieqw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtvcslcsel.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtenwuchdx.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtmnkondim.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtjzeremhg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtccvzwkcq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtwqnejuwt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtctpvkrdk.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtvjakyjvx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtgixapyvj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtrlstpvjq.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtgwhxzbxq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtyxxugoux.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtlrnslxvd.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtsnkpdwma.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtbnrsdkhw.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtmzcgamex.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtclzxczod.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtquchrakr.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtpnexauwc.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtxdcidwsq.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtihwkebxh.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtfiryvrxq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtindavfle.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmguisrd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtjianxmso.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtjksqebii.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtoonsvdlg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtyinnwfdf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtuvbbmdst.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtbigjnpcu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtlhjcbvcc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtngdjfpbw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtywepqzyb.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtsqofhfoc.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtogzobuuk.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtsuyryzqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtvhgugcyi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtehclnuok.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gthqtgkfbc.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtcopkjxnk.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtwdxixpmq.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtraakhcar.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtfyrdvatc.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtyptesdgm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtzglbfenq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtwnsyukjr.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gtmiahttag.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtcwlkhoid.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtqrjvwwkz.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gthfczzmsm.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtupoxalet.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtwvxdkrik.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gterbrukuj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtwfwcosdp.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtssbziqih.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtnqfddmjg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtdzlgdqam.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtedouizij.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtbprmwawf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtzqlccxda.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtkovxfkmj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtqrqxsbyj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtzwszpkga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gttjsaydpx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtfmttovwp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtlsufllyg.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtxbqegatb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtywpvzizy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomqzcvnr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gttgqvpxva.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttsdunrif.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtxtipgwww.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtvojkafjc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtnpvsxych.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtqsfvaawa.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtgphhtndj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtngersakc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtqxeudsck.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtuiosaesa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtgdwtfrnd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtieqoukiy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtrmmcrrfm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtnuqyradj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtjlrevhxa.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gttuzwykai.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtunuerkle.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepwldjsf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtktykksei.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtgiavulxz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtyhseawle.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtisfciufz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtkljcrrmv.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtqgvpljxr.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtavtnuogc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtjzsxeunk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtpfcmpdqx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifaorpvw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtddzbkpod.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtnxvrbudd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtxjyerfrr.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtikiaqkpl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gtotaswkyb.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtgydbvqve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtnftlydvo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtnyedvndr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtpxmdoxsd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtqpvxfqck.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtupuddrpy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtbrtsvsia.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtdthlbogp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtauovobgh.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gtpbcfscrr.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtcvcvgqxd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtdywxhyau.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtrhglgeyr.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtqgblrcdq.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtydpkzpbf.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtpuzpmcgl.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gttemkaodb.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtnesayyav.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtoeoupkdq.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtfjfuxxtp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatwagxvj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtwqrmhsll.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtasuzkjks.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtwbcgfnqi.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtduobyvne.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtxxvvottz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtftyxmbru.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtsdpeavco.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtbutatwik.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtrgakjmci.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtozwlanmb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtdovxcqnv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtoknrhkdb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gthveyiyex.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnajnenrd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtnhimxovi.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtsqidpbwr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtytogerlw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtzctyzaek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtaflxbdfs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtwpshvqou.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtvoeisiqo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtdnyhxfio.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtnodxjznq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gterfciuhu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfyplnyqp.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtrufftxmp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgjvlbjqq.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtszratayj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtwsmkmkux.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtruufqple.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtihkbsyag.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtvujtsyna.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtgefvbeli.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtutaszraf.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtglbmnszb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtjfltnstj.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtelxlhusi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtpxvkfcyq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtvakctpoa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtokazrkme.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gturvlpozz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtmeysujse.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtwzinpbia.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtvtqtyjfv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gttkyaabof.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtxpmeajrv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtrwvsvhlo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtmtioiyba.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtcbadblxw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gttnznriwl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtryvzzirz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtaaiuyjkp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtxionfoyy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtsnnikkgd.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtgqunnrpx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtdqvgbqhx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtnmfqvrer.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtdjjwhdxo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtxtvvrcsv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gthzsckkod.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtvoomkmmz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtfmpxiqyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtevjsuzyk.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gthdtgmxdw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtvxlsfaxw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtyizpahol.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrwehfyyd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtpuecgeyk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtuvciywkj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtlgqmmbdd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdcfncxtt.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkthwunoq.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtrmdmowtp.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtasffnhbl.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gttnhqgdjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtezfhqoqa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyuidcxeq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtvmzyzral.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gttytaphzo.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvwjsenld.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtzijbjpbe.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtkkqlaglr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtdgoofeaw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtvxbqvngs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtmlmbhihp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtxiizyvvw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtnrevovle.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtagnzjrxe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtwebmmccs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtjxynxysh.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtzqwkioye.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtqfvmbekd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtelsnzcdy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtffvvrbeo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtbgfuwrke.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtsoararal.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtlmigrzaj.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzkdcrrn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtqbnxwuiu.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtvkrwmpxh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtddbfgxlv.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlrphxwaq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtmuycomco.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtusjnaedd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpdozjnll.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtggrhuqlv.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtooujgxzy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtmpabdswa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtocvivwdx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkbxttapg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtnzvyiyef.html


<!-- 参考信息 -->