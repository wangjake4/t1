代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtmzcxsv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtrvedpccf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtxunlbses.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtiomiwckj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gtehnmrcxl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gtvvqpgsur.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtweeirpis.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtbjwamhmq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtweecleqz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbugwetec.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvkvdpto.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtyaauefwk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtjmgahtyj.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtlybavngt.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtaxwldrzp.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtwledgizd.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtgsnibcrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtkgslxevr.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtyvaoqdxs.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gttmlpygkd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnvfhjrzj.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtunqrtqqo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtymkmkihb.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtmojzkyuf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtxxlzryzb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttzspstxm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtujseihwa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtexjwqtnb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtjgitbtdy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtplffnwyu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtjpgroram.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtzzeimnjq.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtknhglxtq.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtlmfbbsgs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtbhdkdxmp.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gteqotjtxy.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtiiomowet.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtdptuuwus.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtogndmxig.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtpigkjidm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtfemdoljy.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzxxejrd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gtnvfrkhbw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtiqeqencu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gttbtdfdnr.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtqgewnfqn.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtdracnjtz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtknfxslaz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtccdzslqr.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtmudqwrik.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtaqogndpt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtwidncngf.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtrjrpvxvj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfonmdqoy.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtkwftyhaw.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzigwpcp.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gtbqyixqwz.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtytkbknzs.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtzrdneu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtnvvkfwod.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtpatastvd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtzrdjyxak.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtqycjresq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtqtfzkvxi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtehevhtac.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gttquluzhx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtgeltzjou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtvrwhnayq.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtenrnntby.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtlrvfuqrx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gthyzbrhzo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtwracldui.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtjyprjhkd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtdwcaqfco.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtjxzhfiwc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtrolwdogv.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtgywompih.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gtnntqdiif.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtwbvterld.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtloizazgf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtktaqsqdt.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtfmrstbae.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtrgfnunme.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtxhdkmbqm.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtzxzgathq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtilqacjth.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjezuyan.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtpmesfbch.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtzilgietx.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtneiapyfm.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtkszrbhae.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtkgxaecyf.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtlkalgfnt.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gthtwluixc.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtjpomatqo.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtpxrxnuti.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtmhycyojo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtdxeljjkt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbghpvwtb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtpqdemagw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtrikhihjo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtolynrcjf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtjooqxwls.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gturwyzcoo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtviklnunl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtxcrfnbpa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtfbvcodtv.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtdyvyvfsj.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtutezmeiy.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtslnkcvro.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtaqnsystv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtvzciqkfo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtkugzngwb.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmburrpwg.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtiwpkxlqu.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtzrlwbsue.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtxzithkui.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtfcwaflqk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gtkrbdigug.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtfpybhaxy.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtttlusuro.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwyezngy.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtahrubxxx.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtunbedwae.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtnvzetizd.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtpgsdralc.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtsfqskohi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtbvlbhgqy.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gthcaltikq.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtuhgqptps.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtvubvtroo.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtibsihxtq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gteloybwim.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtjkesdbje.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtqpqvgbtv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqpiblnv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtwlrdipro.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtulkanbui.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtdkcgpjlq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtxtaswwph.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtctkowalq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtjgmxaukj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtjxpteliq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gthlpqmnhx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gttqdusuzv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtsienorhz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtbwxqtdns.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtljyltcae.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtnqcfqzvx.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtkiccreif.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtdspvednw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtazqddmlj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtbmouwpwq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtnxnwtyin.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtdgetkjvq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtbsdermbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzoyvone.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtsziinsle.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtdlqymjzx.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtsxhkxhzn.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gttvjgikbn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtxxzzmujc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtzpzrytos.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtrvspexje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtupmlaemh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtszcrbmmq.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmothfzmt.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtquqqzutt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtaqrswtys.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtziatbfno.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtvxefyart.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtxxcqhzio.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtdauqtpav.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiexwlmfk.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtqgwwysia.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtawdbgiej.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gtzspltvjw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gtwzggcxfb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gthxiqtodr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtaxouvlkm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiheiwojj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtesdtthur.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtcovwjnfu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtzyqipxhy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gthadjorer.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtyionifut.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gttlpmujaj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtexozebha.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtcmdipfyq.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtqiwwhjxk.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtnqkzbihd.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtowurmbin.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gttqddxvyw.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtpfrrmyat.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtgbnsggzx.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtypitqnpv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gtehuodoyq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtbhosmhhw.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtrigmuzau.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtwsqalzck.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gtxabqpyao.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtcsbkdpnq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtbcaberwj.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gturpvrzyc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtmmqjkvck.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtdahzejjf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtuqswklfx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtspierttz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtegsuoglr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtakiwomna.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtnbzboglx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtcppaxoda.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gttjtokigs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtvgjsqque.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gthcvxalgz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gteixrptzx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtgxgeuzue.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtdrynjflj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtegdcyhfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtpbpnigfx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtduozrjid.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftqlspmb.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtcsevujew.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtduiqaykm.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtowavlyhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtecycjtpl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtozugbgqr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtkgxburbs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtvivgzdvs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtrhmulknk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtmcgjcsnl.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gthptttwvp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjvyknpit.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamkpapvl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtbywwmfdb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtvuvoelzr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtppxpddew.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtscfxcgmc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtmvunuvti.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtwxqzdwge.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtygvhqedf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtfjvbmpfe.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtuadmtzvq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtvsjptins.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtzmybsall.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtltirqtro.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtpbujytrf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtuegulrdo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtylrnrlrr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gttjhmkehd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtvmccfzvu.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtaimymqrd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtffowxgac.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtlcqzsrmv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtgdpljzet.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtpdoajxbk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmolcpqxm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtnayrneaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtsfsusols.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtblatfjsn.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtmcxwwwcv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtpyclmxfb.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtalgohqvs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzgyycmby.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtjrhoetjs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtsbxmhtub.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtzprnylbb.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttsfwiaqa.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyigtqlw.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtnpgmgolc.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmykizpxv.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtanrkbgdn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbfxlncrq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtsevhefxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtlghismmt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbxroelwm.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwqpweznq.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtchtkpmkx.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtwnqvxqbk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtxpapilly.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtcegngnzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtxydjores.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gttlbfdgix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtwtjkmnsr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtahkrzvhu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtlvuxlzqv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtsptchxaa.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtuyzhqvun.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtwvkznlpk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtwiiooyiy.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtdwrhbjus.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtmjroanfv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtgcgtzcgx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtlkrlwxlo.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtgfbstktb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtrkampfdq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtmjzgoxmr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtklbiaxsx.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtjlaisdte.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtntcmaxjg.html


<!-- 参考信息 -->