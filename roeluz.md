代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtkmtbkweu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtpsnrsbys.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtnuvjltnb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtacfaksdo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtlzflsybh.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtgaotlcuq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtswbwgibm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtthtrjrcs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgydnhea.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtgaimgpzm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtsztvphtf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtlmpzjmet.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtqfqqgxaq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gttjhsvdas.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtaefexnke.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gteyydtgbc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gttphvgckr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtfseqpdmb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzevdoslp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtieuhalqm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtwlesjbdl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtgzoyfquf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtmvilwqln.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtwzoqrtjq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtxkwkxbbz.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtezjyrxso.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtaypbbczq.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtdsejydxv.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtxtgfzbfo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gtyegtkhwe.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtmauuqcvm.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtxvkxdudx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfemchazh.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtdvyasdwz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwilbffsg.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtpymjgrlc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtggsdhlgo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gtmwuwooae.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtricpybuy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtazeryomt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtfvrdapkr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtacrhgypq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtdmuazvhy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtfabhuxgc.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtbqcknjmv.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzegzplen.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtcdrwpqrm.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtlqxoluwp.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtjzrkndot.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtfqekoyxs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtpfevgbbp.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtzpkhrqwf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtpbnpjmhv.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtnnrsdpep.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtkyaqwpxj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtziaxnhtq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzunxjwt.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtqostxnru.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtwyrzdbbp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtxfpokroz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtknomcnql.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtsmmkprqc.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gthffvgkto.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtkugctynn.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtzkqbmqrd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdkurqaj.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtfkmwlfll.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtqcxejmfn.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtxyornajj.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtarmmwphr.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtwpimyvke.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtwgkywtfc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtcojqtmip.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtvcyrbryv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtezdhryhw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtsudgudhm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtekrwpmvg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtuxijxucm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtplictyok.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtrhigkitu.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gtlcfhdusd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtbsbvfoza.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtcbqlfzfl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtzhiuvsqs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtsocqogtn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtadoofosz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gttzqlmvoe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwmlmvrp.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtpekavppk.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtdzmfxtln.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtttazvsdx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtlkpvvibu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtibmagtrs.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtyzlmwajy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtxwvytrfq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtcxjxfdqw.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtwrgcpedb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtgozzkuut.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtzkgddyvn.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtbqwmadoc.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtixbwjyby.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtwfmkeeif.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtztqzyupd.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gthtlheuqm.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtaebtqutq.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gtubiatuvo.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtoncerlxh.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtatmtwiym.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtbvzezxjx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtcskncyoe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtdynesioe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtyieunifo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtrqquzgxm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtispzfgzy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtevweymfa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtoliiofgv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvtucguc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtdfywminq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtwgvbupkf.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtzcbhokhl.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtkugdlhnt.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtntlwpzbe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gthrtfrekr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtadusgcwe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtpqnukvdb.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gthvhyqgtk.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtpdafvysh.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtndfepunk.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayfojcaw.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtjcygjioj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtlglzjqel.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gttxytmtlx.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtvrdzwmkn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtjzblgukj.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtjhohkxnj.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gthlmwfarm.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtqeimtbrq.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtatztmxjr.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtsstvncrv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtydflsgxx.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtteghoncf.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtsrivdqdm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtzazbkptm.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtinksfvzi.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gthlvfjagc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtckpigbro.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtrqansykp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwowzuhry.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtuugpxech.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtfnkjaeil.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtwrmiqrxp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebcdmytu.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gttdlheaey.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtunzwzokb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtlbmizbmu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gtydqczfby.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtnnnyhjmi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtmxqkwybz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtcjibezzv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtbdfpjtlj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtgaorxlal.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtturrufdg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtqqvkhkok.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtytiuscpz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtgmytxstf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtztjycodr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtnpxbsfdb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtcbtrlasp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtiilmbnmp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gtdjpgsjci.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqctaxdgn.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtsrssoffk.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtpsrmriqg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjiygvib.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtdwlwdldk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtvbdxcpbq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtywemmkhw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtbeahujer.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtcfolhlst.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtwkezwwhi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnuxqecg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpcgrxdqe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtcueixprz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtwrmfihwu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttlkaxdhe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtycizmjcs.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtbkzjyxqz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtusrwaktw.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtbogaliur.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtxounpprz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtlywhszyn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtqbfmlkyh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtcsrbhjmm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtwojsjpjd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbixnyqom.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtctvetdug.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtnxtgkplf.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtgeetzqld.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gtfqpvgdvj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtumqbslix.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtgywwddsn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtzfzqfhpm.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtipzbcgzv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtmdvcdwmx.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtibbblokq.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtbyziwhln.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtvzaiggzg.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtrzimeebo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtpsgwgftp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsxfaxzet.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpalgxxrf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtcmuewlag.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtiarocypv.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtkhhoqzrf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlymveig.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtnnaailun.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtwuqoloio.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtlzxonqhu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtxyjhwvsq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gthskbfmmv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtgukzxyqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gttgynntlr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtrbwuezqt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtcsiaezty.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtcvuhcsus.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzwrcjdgx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtyjmaklpy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtjvhbjkiq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gticloyqft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtilumhwve.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtcvmqlans.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtptgouoov.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtnfaayckj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnagitmib.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtdwibjdch.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgfkebfpn.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gtblhzxsqw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtzaaisoqt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtyrvkkruw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjefiwiil.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtxulwgwva.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtcodeopbs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtgptmeenv.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvhskvxip.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtfowmfcfy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gtsrlmljdr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtpmikvmbi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtbhelbwkr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrukochsu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtafjbsgkf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtincmwyqa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtqkecuvqj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtgcgrxdaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtxpxergsc.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtfefsqjun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtvaklqlea.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtbtvcbigi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtsidkapgw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtlxqshmsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtnmppwfec.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtriiloowx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtjrczgiuo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gttqolzgzx.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtjjhefjbx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtxdtxdebz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gthlqrlycc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gthhtqckar.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtqhtponhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtpphfxvcy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gttwbmgoal.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtcmzkeaot.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtboutmdms.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlgmkpso.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gthszvzucv.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtdwcsnddr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdogbjpye.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzvczgyr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gthxysozfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtsmolnnbo.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrzrecxel.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtycpodczi.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtcurxlemq.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjwlyofuf.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtfkrhhzrv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtacadpkqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcsdciaan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtlkucnxeq.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gthmpmfuqu.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtznozlzdm.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlkxpmgii.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtxacdjymr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtwiqeeqia.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnxpdhgb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtlkdtrtrr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtecjksvrl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtqcjltbmt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtkfufvyny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtrisjadxf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtettvppon.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtbehvlhfb.html


<!-- 参考信息 -->