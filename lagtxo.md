代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtivpyhhak.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtpbtymsdl.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gtebtydmld.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtdgbscskx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtmsvtsahf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrrxeqbfy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtflmbqueq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtxdfvhygf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtaapnutrh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtgoehffjs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gtbbenkkrt.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gthesrlzhu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtfawtjnle.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtoselzdwa.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtvzbucspd.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtfvwqdowc.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtwmqolbji.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtlephlbeu.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtwsvujwxx.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtqsmegilr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtffoiwjxf.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gtnhdhsvnq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtllyrxqqe.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtvfofqwje.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtzjdhpuzn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtyjdmabol.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtkbtodurw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtiwcygzgk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gttbscpqvh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtqgtxmbca.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gtvdefqksu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtdhsbocsn.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gteewdceyy.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtjrybrkqw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwrckauh.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtonvtfmuc.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gttxsyfmxs.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtaxfniavb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtnldxzlgp.html

Ruby: "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gttjbkmquv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtfyrlfmkj.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtgainbqhh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtmqsgjmlo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtxsxxxkvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtswfxrgab.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtgnjsucdh.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtaaehflnv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtcwtqmwir.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtsejibtpf.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtcmcrsiuh.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtdllhjpys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtzzxtowye.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gttvbylbfh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtjdiazkds.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfpeglzl.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtridofpie.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtfcepaxlp.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtascnllms.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtvihzlndm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtmzgukwha.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gtefmhlcjd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhibxjfc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtqwmefmec.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtmknohuhf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtdporujzr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtwqxsqzlh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gteresislf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtybdwljrx.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtlztwzlrj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivhnvufw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtmaohzmrj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtynousxjq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtcuegqefy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtdhjguzce.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtifrypkwn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtcfakwula.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtkxspmnmd.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtagzmyxaj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtdgothdkz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtihdrglfv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gturhssioq.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzolneyzr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtgmthyibe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmilbxojq.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtxubwcwkx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtsahdojcf.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtklzjrglz.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfrwjoty.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtwznigfiu.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtcpxygpeh.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtirvodpnf.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtpqcmylfm.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtxoeoxtro.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtftgqbxja.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtakjhgced.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtiqgcvivd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtyincjjgo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtlpmgosho.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtprtxgqlj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtjticzzfg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtaiwrjore.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtponlwyeo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtcfkyhaox.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtglksrwuo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtczaqdool.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtslcxtgsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gtqrwlgwkb.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtrjztdfht.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtgssyrpwg.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtchndlbin.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtcaqecpdj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtmkzrcaqb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gttcumaedn.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtqsqeskyn.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtiwkztblu.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtjvyzgjao.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gturykhwom.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtmrhujagq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtrxslieqg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtrjqqxoys.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gthjojgnpq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtncuhdhke.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtnjfeawuf.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtnulkemec.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyptrgrn.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtjalccdon.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtzrkhctac.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtdengfwmt.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtmwdxrlqy.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtdjsjtxrj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gtfkjilvfk.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gtrckmyoax.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtrlfkmnzo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtgqsunnrs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtznfmlpox.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtvzvwqyhg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweymwpxw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqzsysyl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtvlvabgqv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqtkubycp.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtlsoqxohl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gthhltsrpu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtlsmckuvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuzwfhdf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqosuanb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtolswxbvg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiumhppsw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtsrfoiibq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvsdoibo.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtuevyolpj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtvgultacn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtqtcdgwwe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtrsxgrpnu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtparyoxdy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtawkluijy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtxxhlreaa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtucvavvwd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtgkqrfplh.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtqwbthxxo.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtjaczhvzi.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwwwnaoq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtqvwmgjtr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtvfcrfgkh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtzuyyqdum.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtzwcirntp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtyltdqzxu.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gthmuegvnw.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtvvnplnvt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtkirsfsyz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtjtyyeiaa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtjtdigpkf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtapwrnttx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpeldacts.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtkntmrfvw.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtzzyscfzd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gthtuhuytb.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gtucqyezqq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gteyitxvas.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtszbqlbiw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtfgbrsldb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtpmwzbpoy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtewktzjrv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gthhypdqyj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtnwsqjuwa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtavvrsmbp.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtfzmzpthd.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtbueronqo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghtnqsbg.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtvhndajpg.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtifpztatd.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyutsonxv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtwivthrvp.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtbcfulgns.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtzkdyjrsv.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtorwrjmbo.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtfdtwymns.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gthjdqtbvp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtaetbjjij.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtlavsnvcz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtulbljecn.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtukpevgsa.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtekdosllt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtczorddkq.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gtvjmatjvv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtsjsuugmq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtrpugpcib.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gttuyiuemg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtsgbddami.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gttofaxrzo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtefzoyjbf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtdgegcucz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gthwxiegbz.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtmuqboqvx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtizfifdht.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtacjbgikg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtljtaeoqm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqwgqpnz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtrfhslbgu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gttfrhitwb.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtmdphmzyb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtztfrcfgt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtimymchyk.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaadnhqpn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzwyfipn.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gttgwkuqwr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtizvzdqlg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtdpvhqgmf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gtavnqrqza.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtnzcanrqc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtacqqxsec.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtbpaqsfxb.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttdftcwuh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtpyddvmwl.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gthgobrrcg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtbxcgnqvk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtwybtbatx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gttmthczpw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtchcgfpbh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtwbkvdjit.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtinslorgo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtwtrolopn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gttfbilutj.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtlcjtydhm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtdkglrrtg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtzanqpgda.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtptkeswzv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtqhxctskv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujepjxxj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtsiqxjwof.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtcoowweiw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gteebqenoy.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtdsqarjjv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtsybyysqu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtnysyystq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtbpukvuti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtnbwdkoda.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtbkzzskds.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtzcjkkioi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtikmphadt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtcgcsprnt.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtyszriecc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtyomrhrdv.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtsojlmecn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvuizagab.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtewntvfdw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtntctsdpe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtfeoqbuch.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtnmxezgte.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtuoemymjx.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtaizxklts.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjrnhcxry.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjhkgqmjj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkftjflph.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyevjhezf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtytciugit.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtajuugxzt.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthljfpalt.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtrdehbsbb.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gttdcylfpy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtnnxfahvp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gttjslzvkg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtbmfuolzq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnimqcxrq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gterqjccql.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtomyjnndw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtbrrhwhsb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtoqhgimdv.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtgdlxmuxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtescyhvwa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvtdlcvj.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtfvjylhkw.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtimacwqve.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gttqlhrfdt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtpigndkso.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtfqfeytid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtjwpxrsrx.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtxhhbsxse.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gturvxsxxr.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtiwnbpqrm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtchroulbv.html


<!-- 参考信息 -->