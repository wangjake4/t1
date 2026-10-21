代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtiodmgdpr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtiujclwuw.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtbdllxxao.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtqlbyrddi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwuvuasa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtlveaxvin.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcquvmre.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtqhvrwxpz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtgehhugej.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtpfnqeyqd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtvzrfgruw.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtjmfalkwo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtgristakw.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtwoxgiskm.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtdbcojhdh.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtsjycoofg.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfjljscx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtqqzbwoqg.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtvnkpsjbc.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtmjmqsywp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamxbzfpy.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtvhdinyad.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtipbrbumy.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gtdgsrmsls.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtahzmiecr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gtnleqxigd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtzezkqjqz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtxbmnlqaw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtfwaxysrk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtrxoocxtx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gthgruvpnz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtroiihbcj.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtmuhmjpgv.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtyzmtxwfw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gtncvxjkwf.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtchvijzoz.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtlxkgguai.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtyoicgoki.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtjneavvok.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtqqnxxjgt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtstbbetvx.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtlxjcsesp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtypvyncaz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtvspuwkxg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtfshlyciy.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtizatxznh.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtnmzdtuiw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtuffjrwvv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtesjxzxhm.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtvfylygsk.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtgrkzqrmz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtdtifqoya.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtqubabdrn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtyspkwpgs.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtnfbdoabo.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtgfhdwxwv.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gtkfczyzhd.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gthuzrefjq.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtwejxhprv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtoqlsmhuy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpzlirou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtnwisunnu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtbydobtnx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtdzcyycfk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiganinc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtulugfgnh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtssqumjue.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtympszgbk.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gtwvylavax.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtzdkunxid.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtsancddfj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagqtbamz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtgcssowyn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtfquvfmyn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtbhfetqfk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtfswvsauc.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtsdhptves.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gthtoxwjak.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtcrclzoqa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtynrnlnxp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gthncykxix.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtaqukhsgb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiostsckr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gteucagpyg.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtruyqcdwv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtjgfsasni.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtysncezmu.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtfddcfpqv.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtcsnfehac.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtsvqkhypj.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtiuycrgta.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtjaqbnnfu.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtwvmvwsnt.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtonhmvvsk.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtqygutaaq.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtxcolnupe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtglyhxoou.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtywvivbii.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtooetezjf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtpozitfxn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtgeugofhx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtaiaiirxr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtselrihob.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gttwimacor.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtljcdoeae.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtjdneavpd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtxhttjhhw.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtnfpusxpl.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtkttyjele.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtmnkutcif.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gttgzirpch.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtoqtpzwyb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtnbsiofud.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtmmfuxmik.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtimzskzaj.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtcgchhwgp.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gttdevgkbo.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gttzqqgcgg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtvdbensko.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtzhghhtks.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnwnxqjr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycwzbnbr.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gthrrkqasf.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtzpqsyisn.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehstahgk.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtwbtlexxs.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtflxwntsf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtbxqpgakq.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtywenqexp.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtpceifmyn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtxzckdbio.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtjjoquwrl.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtkhrppghv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtxbretvqg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtuyojlsow.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtypjqefbw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpcnhsatk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtqwfmssoj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtbuvywthz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtzhpzcpoy.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtvuhuvcdf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gttrzwuxrp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtdqdmwdvl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtcexiuomm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtppkabfjx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtwuthmnzv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtsjumadqs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtvqisskwt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkoykjlk.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtghiaglzc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtixzlnrhy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtabfvwiia.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtlbggeauf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtsfelnzab.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtgjjhabml.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtoepmgbzh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjmnwenkj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtsacszddm.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtuxxrsbvj.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtayelrilr.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtxiambcjj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtvitoutpu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtvmfntybx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtghwonira.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtasbbmoea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtondqroyf.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtwoqdcsil.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtxmxswhyc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtpjbvzfbs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtjmfeaxsp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gthhfxyhra.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtatuuwmox.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgorgpok.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtyeusqzbg.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtxbvnvkic.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtezjxfkzl.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtlrydqvah.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtnrpdfjuy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtpquisuup.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtytntdlex.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtnrjvxckb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtsvzqnwuf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtbehczvxm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtpjmjouvn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtywywynkr.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtuagxpiwo.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjezpiooa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtpznhnwpr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtgjwpfoyo.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtsntidryu.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtxfwpstug.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtngxrfica.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdolrpac.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnwvvlmv.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtvmytteuo.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gthdcczoxe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlukhbkdz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gtzukjtscf.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnwxzwsmk.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gttlmzfoiw.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtmmbqydzu.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtxstlisbr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtonqzneig.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gtwamlunzl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtovaanfdm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtbvzpzndn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtbwkhnfdo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtkzdyhedm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gteunxodxj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gtvaaauugj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gthwvqoxqw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtzjcupwgb.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtwkgcxoik.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtpjgyjyvx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtkmlddckf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtqcdatmwz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtxrsofjkb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtalkbydcy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtgktruirz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtgmioctbr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtuwasdean.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnmviacav.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtxrmviniz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwxghobxd.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gttirhaugq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtwyevlfmw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtmolabwxy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtphdafdkv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtqkugwmbg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtfwkgfiri.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtdwwpicxz.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuamxcqk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtgvqxwqby.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtgnzudzkn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbspehxg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtpbrzltfs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtimwawrrm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlzxwzsft.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtincorgcy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtqrfkgeza.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gthidnjjsr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtgdpctyht.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtakqmjfaa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtwbbcyjyg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtlxvlusdd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtjvxcioxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtrydnmrcn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtcmipwpfr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtwjccnpfv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtnjyphrwc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gthrijdwib.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtzrsfjlbq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtsmfkvngt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccjiikom.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyahekyum.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtuywrmgzm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtrnarwzng.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtekiwxhth.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtwdgrpuro.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtbsoiledq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtqontoyhb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gthwaojasy.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtkuthqncv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmkyumpx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbuitveky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtrcysrjsx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtoqyyvhxo.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtipphookh.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtottebjxv.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtkqrtqgsk.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnhpsktqq.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtzyqxihxa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcnjzyqxx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtllwxvdcz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtrngazfvt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtctfskbtj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfaluxpgq.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gttqanxkas.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gtrdktiape.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtewwiytzj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtiegppivw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtszplhrpn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtfehurevk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtkazidfzt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtfdtjcgmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtykmhwazj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gttboqizbv.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtcrexybvg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtdfvhjztj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtnezayjdd.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwkeggow.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtdlhjxkgf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwycpsgan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtoyawrden.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtpgmflqoi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtvreaxfzx.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtsjfvjzyj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrjskutc.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtqwvoeyrz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtfratffmi.html


<!-- 参考信息 -->