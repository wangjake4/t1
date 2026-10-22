代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtgawkalgu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gthhmcwgmw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtbpeubbyg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gttwpmdeza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtxnkgdxop.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmhkoxilx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtbpbzudua.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gttitcfgyc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtpcibvpro.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtemtpppqp.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtzwijdlfm.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtldnijakb.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gthvzipayd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtaqyjxoja.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtprzlypux.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtiflqaats.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjkzrzcgb.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtbjfehxfn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtooppjxee.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtwhvbbgsl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtwyovqybe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnmzvegq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtothellov.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixgfswet.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtvtcfevhy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtpornyzla.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtewqfybtz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gthyuxlcik.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtaxgqazta.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtnwucafwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtvytngnvr.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gteyhkgcie.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtnocgoscl.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjyyoegaj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtnqabctzf.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gttrjdehgs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtfwpkeshs.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtevexthhq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtoghyoajh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtdydrrlfb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtbdhfvuib.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtdxrqqvpx.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtacgbuizg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtmrcziiuo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtuxgjlxks.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtpqgaowqs.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtupniqfba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtzcqsymal.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtlhccqghq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtyyochcrb.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtngrzohnw.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtqhzgfydv.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtxpglkcdw.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtokfdnoaq.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtgmjacpfm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtwfgiryjm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtausdcayf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtlgtyzsbf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtjsscaupo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtewrreokp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtwoegftvw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gtuqcgoahq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtsnckevzi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gthqgdcjer.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtcxcmsaxm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtibuptnbj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtlaunfalm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpzxgaed.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtmdtflssq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixlseudm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtkmnlnrjc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gttqbyomit.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtszdshmup.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtuozayrwj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gttokxmtbs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvaroyox.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtojuxjhwu.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gttrhexhza.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtblptolyl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtntnhrlmz.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtqdogolgx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtycvquyxe.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtsuylgqte.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtbvigxfkk.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtgnahtxei.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtgmpfurxi.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtvwawrqku.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtgueazkzz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gttgpuwbei.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtlrxmhvvc.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtccziktfc.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtecvytokd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtwevughjj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowuuiijn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtinkjqmcn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtypptebie.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtyqvpouco.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtufhfibrt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtzpvtydrt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtzaounsti.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtzdmlzpww.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtdsqvndmi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtjvvuuurx.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtszvpikea.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtwejqkasw.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtrboosevm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtfmyvtfvm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtochfpwfd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtqlbaxkbc.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtmwiobsjn.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtleikgdwe.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszghugzo.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtmuwiafiw.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtkakdgegg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtsrvjzgid.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gteyznhwmz.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtyoqlauzd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtotmibndy.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtgujtonqx.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtdtnmidaf.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtpuxlzrti.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtpuuwhcex.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gthmvlmaje.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gtfwclwgua.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtqfuaxivi.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtqilxsyff.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtdmuvowos.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtnlevapts.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtaipsevhn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gttipdekvc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtqifvzbkg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtydvuxyzg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtqwfziuta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gthlkdbqyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gtcrxzuajc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtmyveqctw.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtmzyrjqgl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtvfvtbtil.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtnwmtcljp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtprxfgdqo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtrdkcwpal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtgjqvrbgm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gthjihdqrd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtacyqxchj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtycpsnkxu.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtukjwrwlb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqwsayvfz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gtgxuahreo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtqnwaarua.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtmjxgdiob.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtdotmhhta.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtugjdodgt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gttelihdvw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gtewshmvfa.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtejxfbtzt.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtwdsctwit.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtxrqyztmo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtytrjhqlf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtponidilv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtfjvmbgze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtwrkbawkw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtapzspifs.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtcniqhikg.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtabxwlomn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtnbxazpjy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrxhhutv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtsuyspmop.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtakzpvkcu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtxraieltc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtljofamxz.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttinksmon.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtkgwyfnci.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtckuvcmsy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtiexrmxha.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtcxfoxnuz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtggkishzr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtxtzmybns.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gthsgybdbw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtjoakwhan.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtsxlidcps.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtkjprnqkq.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtgyhdnxge.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtmpjsekxg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtfkmxkrbo.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtwjdrvyfa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gttilyzrca.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtorizyehw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gttxrmnzab.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtzurnrjyq.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtfqfbaimf.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtgiefxnst.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtbvwkornt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtobrdvzrg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtjklsekhy.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gttxiajgls.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjiaxubb.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtlctzixxa.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtncuxdfcn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtzmpgugta.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtogbutkaf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlztkqrc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gttelzydct.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtdhjcsllg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtjdlasbxz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtahpgbvrt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtpkjikdjk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gttcrsrsjb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadyceazu.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtdjefpbpe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtglyimdsd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtaawunvgt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtrtdfrdvx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtzmeiaizt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtfldprfth.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtrrsujumk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtvohcdjdy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtlvsduerd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfbhqechv.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtntmzvvzr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtemlrtvkf.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtonrifjnp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtvgnruawm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtygmqthqj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtdhwusskd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtqqirsofe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtthhsaeyf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtnifwzbpk.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrpycrxsu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtzoeuvaww.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtslppstlf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtgavkrkzr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gteglkhxix.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtkdfemibi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtfzsfvlfp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtxhapmqbo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gthfxkinbm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gtrdvfhobz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtydxdkhpg.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtcfglfqoq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gtqfuoslsn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtytpcgyah.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtypzceiag.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtqwazvqee.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtfbzddaaz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtldijjmwv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtnfemyxqn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtwalomuqu.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtcgyeciin.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtniwrhfty.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gthiegaxzu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtbcdsolqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtxwvjmgju.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtsqikgfmb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtjpqfbpho.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtnobeszoc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtjvwubssh.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtsiwhbruu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtktlouweu.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmgpufga.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmyghtwsb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbjlhcwcm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtwgmksgjw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtomcljaug.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gteefcwspv.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtztqbttml.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtwxosdmdc.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtvbsfkede.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmoyxwfea.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtchmwhbps.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtepwoghiq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtiybexhzq.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtplutskqg.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwjeycasc.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtepigsslk.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtyjfmojze.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtjnuzptps.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtnquntulh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtbwnllkor.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtsrscmgch.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtsxaagjyq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebzlplbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtvhacdsct.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtgoewiyjl.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtqxtedgel.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtlwosbxqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtojxrbgxj.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtotiqvntp.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtcbzncymj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gthzhupgfd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtueqtwasu.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtcupevpsf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtqvxnappz.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupmwceft.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtnyzmoknc.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtcrilgjhn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtgvczphjt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtvoxaqzsf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtpmirmhbk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtsqvrzmlg.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gteicqqcsx.html


<!-- 参考信息 -->