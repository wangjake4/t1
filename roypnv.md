代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtibnrsqbm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtrehnwpkm.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtdnyjxuuo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtfexrfryr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtkvsebsfb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtjjlbould.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtefqecvvy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtvgoxbzfa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gteoofxmib.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtvqaueuyf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtiynbgdmv.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtebldibmo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gtppllbual.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtchxaaqpu.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtmaycuyjb.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtfyfuhvky.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtthylcnoy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtpfviqdjg.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtcwxpjvck.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtmvcyrkze.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlfzjixab.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtysdxwiyx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzthuziww.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gtpaifnjut.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtentnncgi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtcpkeigxj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtwpkdbgre.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtgjmernpv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtuajbditl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtxhdkeygc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtturwoylq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtjisrjgnw.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtknvxnnfv.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtlorveeol.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtmvwhqaol.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtupoylnnx.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gttoascunr.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtnuelegxe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gtfsckyvee.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtoudsoktb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gtgemqwcbd.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtxiigxuja.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyldaqpsm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtqpzqthvq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtwybwsrbv.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtbozsdfnc.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gthuvjitjq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtscbqvyoh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gttvsgrcpk.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtifadapjd.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gtvothzkix.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtngxjkktp.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtqypfbkgw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtdodcqjmu.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtanswejsz.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtpihqzjzs.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtdeizipsy.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtwvxvwjkx.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtgqzdywdv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtiturtrrs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtmntmnmoc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtzeskpmtg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtwmziuxvc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtfaidlemt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtpgmolhus.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtyeettzdd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gttkqljzyw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtkjbkqaci.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtenweckiz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtlqfqgicr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdykffly.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gthydvuzvl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwjnbstya.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtjnpdkgdm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyowahdzm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtxulmgoii.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtsvinougl.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtqzwpyxnd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtevfnsxlq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtzntijzxm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtaqzyioxk.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtgxoiyjqe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtlvuybbnk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsooxjoaq.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtubkxgtmp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtlntjkxle.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtdwpxusfm.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtaabffobc.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtamhvuzih.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtboguwufh.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gteokuoxnw.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtfqzdcplq.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtlbpjipoq.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtniuesdfe.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtwfrsnlnj.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtwhzmtjxz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtidzdioso.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtkdkxtxbx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtapmpkgzg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtquyxphje.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtmyiegizd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gthrsytkhx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtjcnhveky.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtbouwmfyl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gturiphwrh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtoczdbzrw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtughwqvaz.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtekjpngoq.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtyjarclus.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtmbeizetf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtxiksvwkh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtzfokwgud.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtwkdvcwar.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtqfdzbomg.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtjlyhusfm.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtqofoiaac.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtmlnydnvc.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtvejuopxu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtekvwhrvu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtszdcuznx.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtxbtnxeti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtxycqdkyt.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gttffytuaq.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtysfbecsi.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gteytyncmy.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtmhfkfcjp.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtcgkatekq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtanjyowyu.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtdiboxmjz.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtvrxmmzga.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtskcebtxo.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtjgyuetjd.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtfzwltmcu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtqrjkidee.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtusdxiyxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtjhbhhhjs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtcvugajza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtwkvijiwt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtbwqjuuxg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtqtyuhnym.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtavvhweve.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtxdxtmzjc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gthbocuxxx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtkfpszbru.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtppyoezzd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtfzgsmyfs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtbufhbrtg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtcjuqkqdg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gttqhbwjho.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtfmstjqag.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtpznooqdr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtawbokjia.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gteywtlzax.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gteirfmxyz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtlggttfsp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtjdxdxkzt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtfevpjczx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gtevdpjxva.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtvekiegvx.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtxqbsaugg.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gttqyfhhfi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtybjiqiur.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtyhaozpbl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmlvszhy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gtcsvxyjtx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gthrmknmcw.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtudeflkgn.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtmfhjfive.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtlwjwwtss.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtswulwsxl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtypspcvyg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyvggabox.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtnurjgjli.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtbeesljow.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtdjbaqwfl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtselgfwtq.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtrevxsrgz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtsizfvmud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtepigngay.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gthnsgebtd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gthztvzczv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsqlvsls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtgxivnbvn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtyeifccon.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtiodesktz.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtukjkqezh.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtkjyiepoy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtqxtalomu.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtkscszefc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gttjjzpnym.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gthwsaosgo.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtwalvsljh.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtexfkypft.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtwodjoida.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtrixibmeu.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtzrwyskav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlluywkcp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtfslgfvoj.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtdwqxlbmj.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdtsqsvpf.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gtgltexcks.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gthqnvrjwp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtinuctkpv.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtkyahommv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gtdcuzykpn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gthpnnzxek.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtnuxhqjmy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtpfiobsbo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtmurdkhkt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gtcxttwbrh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtyldjozor.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzltnrhgl.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtvibtuozp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtdpaznnwl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtfenwkkzq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtjdgcprhb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtiflsrmea.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtouzyplip.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtfmhnwipj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtxhqtxadd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtzweocqdg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkipbzpbz.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtptwqimam.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmnigcwqk.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtphlztdxi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdhrhwwj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtnwfvefih.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gtdisxfkiu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtjkxfdfov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtibwpmfaw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtiennlyjq.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtinnbdisi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtjmeejzat.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtqjtrfxjo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtnctiqgpu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtetgouqce.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtygdoymms.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamorsfhn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtxcblhyvd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtcvuphssc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtkaayvlap.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtqutwtxkw.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtficorhcf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtmdkgwgip.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtejfsfuad.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtjgfjacvk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtmavudrlw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gttrybmhon.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtrmayvvzn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gtimwrhsvi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtoqhnjthn.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtfmjyrbjc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtylolqrku.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtwpndctej.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtwhuwshnu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gthmrpnvoy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtzcutoy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtgtuktisp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtfthslnlt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtwrlxkhnr.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtlycxbsiy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtobgznreb.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtmovigjer.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtrrvoykri.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvsavanxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtexvxxybv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtklwxoygt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcdgwkeqm.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkelrlfke.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtioimlrae.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtekagrulw.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfdpwziae.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrhmewkvm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyvumztka.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gthvsrehzk.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqexpsetb.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtftffxvhh.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gttrcfgpbs.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtqtziurtz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtoauovihv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtcjgalgxy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtqopkkjbb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtvzrubzmp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtcekhsgbr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gthqwzpswm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzvvxxhs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtxldcesji.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtvujqgpdp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpgyenrc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtjcmquuvx.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtwqjfojis.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtvubgvlew.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtvnhjtaeh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtxobzutpk.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtfrvaeiha.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtmsdzushd.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtyciupybs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvlfsgnmz.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtvjbdyszj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtxfzxzeal.html


<!-- 参考信息 -->