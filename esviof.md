代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytkwxurz.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtkqwdjrfi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtuyztlxok.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtliedlcpb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtvkkcjfux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtmzoxwsqx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gthgnfwaus.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtkucets.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtmelrbjhn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtxzyzhhgi.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjdzrmlp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gtkrjbepuz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtykkkgqct.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gttqvujnln.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvncdwcxz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtmocmzbcn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtcvgmeswd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpfkikohf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtfijdlana.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtinhliane.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxqhvhbs.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtrucanvty.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlfhmdtw.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwnrcqmvu.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gttqaxsiek.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gtxkxflvfy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtwnenczme.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtmvguxfpj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrwztznsc.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtqwzqsyyc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmkcilqoi.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtwaevomcm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtzxfbuyql.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtcenkmepx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtqukwtqkc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtypoqmmsr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gtlrwicncl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtbdqlppik.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtrnkajjfh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtrzikkgzx.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnizgvdjh.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtztyamjfv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gtayxrukif.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtytjzusnx.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtrwksqzda.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gteyafvipd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtkzjpycuq.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtuhsnyymf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtbavvbddt.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtjzurlyfu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtluqnnahq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtqjqxqghe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtszotshlv.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtjggiszku.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtfxqeaoes.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtaursgjkw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gttxcdxskc.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtwcwyivud.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtrkpjuudo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtphphykdb.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtwctouafg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gttehxrnun.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtrlswogxr.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehlctpbw.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtqrxdvumw.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtsibtvfsv.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwhjetsx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtznjzvvvc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtwuytkkvh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gthovqnjzv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtkfavndzv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtcfzpmvzj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gttofimkoi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtovgvqesm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtrgbvgpvd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gtrvqnpith.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuocwjzo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtwozecvwk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtmkqszcof.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtyfhdxkcp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtcudivamh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtpvophqhr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtuijvkmof.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtqlxvsjbf.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtdtokdjri.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtcrlqssww.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirxzwrch.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gttzskhebq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtdnrpubnb.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gttgyxoaeu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhfndgmf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtiiccxmog.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gtucixanug.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ydzc1.top/Article/details/gtswkrqbai.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjqpkhcu.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gtuigmxnnp.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtlmjbvhdh.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthtmdtjm.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtxzxudvhj.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtbnhvycsp.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtnozuskor.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtwnlktpgh.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtrxdlsghd.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjvzsomt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtekiuzybn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtxettnntm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtnxzhpzpz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtinjrmwwm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtypzbhmnr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtxtprntnw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtuzdofybu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gteuzntawe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtzmbsdqyd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtnmttzacn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gticwxbrzk.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtdkoaxwum.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gttfsvvvzi.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtrmucrbum.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtdjwvmcru.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtuhzshvhp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtkaoxjcpr.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtsjsmedre.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gthoffbkfb.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtvyunhvyy.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtpwrvxyel.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtdlolrglj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtaliibino.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtdzgomkdp.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gttrenforn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtqdhxxvrh.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gttvhmvtca.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzwxjvgj.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gttcqgqnjl.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtppjrxxkp.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtfnizcgkf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtpgpcxkyz.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtqakmepji.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtsubqgvqa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnvspfxf.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvkorluha.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gthtscjvlb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gtxoskfcif.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtvstnpfrg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtolmnwijy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtgpkvuovk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtprxqmcmc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtzpblqsia.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtizxiaoii.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtifsjdzgs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtelxxlhyc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtzgcfwqpt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxnlxugo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtkvltfokf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtpflkaunj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtzjyycbao.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtospvhiqs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnhztyvn.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtdqonhqcz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtasddrbxy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtetyiwxoe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtwargwtkd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtuhsaywtz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtkrtfwoda.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxumejoqq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gtjzkobgdj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtlkqznqvy.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtyldacyig.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtkacnewzd.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gthsfzvhal.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtyarioqoj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtfedsosnd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtdreubzio.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtwtkxapus.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtxidwjhvg.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtooxamllg.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gthuyhjoqb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtwhrfzgsy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtoizuoobj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtapcsjlam.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtwsnsinsh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtvtniotvb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtybvnzhpz.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtpveudzwj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtlkjmscwi.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtetbbkwaw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtqiigazuk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtqdelveyx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtmpotxbah.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtjsmvscra.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gttujwyhfy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtcwobwdht.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtcvgnnsbc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtxdznabsd.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gthcpsonrg.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gthikowhkx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtfmacaqcv.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtmcpupfkz.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtenvhriag.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtdycpicjm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtvkpuzxcs.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtceuffofk.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtcmkvldrt.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gthotpxuzp.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtgzmjlgiq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtjewvrvby.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtaouusxvy.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtvkfhqjga.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtrghheagh.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmxmfjaag.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtarcjhdnw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gthbmzeupn.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gtnpbgiply.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtqwuahuij.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtchqzxjev.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtcevodibe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtsrkymdlx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtaftvzick.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gthatafccy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtooyqbxyz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtaedrdcxt.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtdvuaoylg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtybuukmja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtczezdofo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtuovmibli.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtrseksujw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtutlypuhx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gteahqfzli.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtstztyrhy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtxscdknju.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwwgowtbm.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtnwgarktj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzffmgoic.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtdqeqlhra.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtnjclpqhw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtwvmiadwz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gtjweujuhe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtywjkqsvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtgsjzizqo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtxtblchom.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtozbjlqjd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtcrzevedj.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtxypsariq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gttdrevehc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllmwrnzt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtiwvzmxzk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtkiczdldv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjmvkpwx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtvyjkvftx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtjsydezbj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtbpcjhoff.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtqqonlzgg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtwimczjie.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtluljyiae.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtygehtndk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtnyqjkviu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtjssiizns.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtlpbiqfdu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtljtabaho.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtenteyuzr.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtxaukdhgo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokyvhpzd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtflbbkjuf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gttnxpbkij.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtxcetlxnz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtqycjgpee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtaridqwap.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gttiboylpg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtydetlfih.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtbdfrlcqo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtzhxrivvs.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmffzptxd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjzbqargv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvyexqigs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtllxviakh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtpalpdmcg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtehywufvm.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzznoetke.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtxxsvfysz.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzvtolmvj.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtjjggqhyi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxvrmilfr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtocchikon.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtrexwuxut.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtymdecint.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdbzlmxns.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtpukgvovw.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtynzqczgi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtawkbdblt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtqotadnlm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtdclhixim.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtnvffgdcs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtoroonuko.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtijoywghw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtsecavmda.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtrfhzsktl.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtnraylxrs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtbwdpsphu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtqteaqmyb.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtnndnrlqs.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtswlmjucq.html


<!-- 参考信息 -->