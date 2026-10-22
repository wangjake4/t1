代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2daqmixey.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsweuyt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpohahm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2twihysip.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebcvtgd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzdtxgw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjjbyye.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuswien.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgowrefp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtifyyfe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrttpoz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fudtnvmq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbonyrlm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxsfbih.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbsidzs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbclbfo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsmbudc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfohamo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsbgaux.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2phwdnzfh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkfspqy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeehvwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdtnphm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsrffpn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyffltj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnwylxu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtsxgux.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrrtnby.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrtbgwg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnpxqjd.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2moqyuxfb.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofirjbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jilgooyo.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpejobxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqsvcgg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2boeyjgqe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2rlelzplp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsnbmds.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jduwzpku.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhlpqrg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrzfuwc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2asltpivk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbegkdt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhksyvg.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qczbadcd.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcpsdfv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egecvvxr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxcojgt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2leklgdxt.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwlqymu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvzyjnx.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqgbbwa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfhnll.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxvbcnb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxqppnl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2naajtwhs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfjxdbs.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmibnmcb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2puestmbe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoyxkcl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdvgefl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqxnqhy.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2fzseisxq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhisvde.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2mytkhdfi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtxfhjg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcytuxo.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2avrctbts.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfbxmkq.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zguqldgx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyiedex.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnybslo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtjaamb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooywmarq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sejrxblj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2izhocgum.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcdzaxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsdqdnl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vimcjbvo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uczkxmww.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tuykuiuf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxjlldz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nekyqoym.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yainuqya.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwaxqk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuosxavm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjvglyj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfkajja.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmgmunf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrcfnas.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwnerqz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2blyyrioq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2unecwskp.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqfmylj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfxthee.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdkwikl.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gdinwgfr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2louankyj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cajmdpli.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnfkgue.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2etkncvnc.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfsbxgg.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsloiqo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavbsczw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxaaquh.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvrwqog.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcthcbx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxwdqdr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoifeln.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtvpqac.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2czudlnjk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnotyct.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkugivcl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjhgism.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2njrefjmu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2izbgxmpf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2yqylgftq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqvjonk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyrsuqd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2twdjdhjk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zculomng.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyfmpbo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqjpqqn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsgtmji.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwjhsco.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghslhqkk.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbhzwcw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmephpl.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqmpymo.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoupwog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpoadgy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkvymtj.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pnanpsjm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2taahfypd.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cukmmfrg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnbrpnh.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtsapnk.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mddhiyln.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwcdvnj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwbkszo.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdadyeb.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlgwcio.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2elspuely.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2divbexzw.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpypdnt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olechjss.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdliuqhs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjjejhu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2suoygrgu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2spxnlzli.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqkbilk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgvigiw.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fatfowno.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pugzaxif.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrorhjdb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2giddsrbc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwursjyy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlaxoqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvyxgeo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yllaygye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mupcuepg.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgricoe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeugoxpb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcouebb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsatcrk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxepxrx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zrywyirh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpnpoag.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2luvaoxgb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icpipkgj.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lxswjlvk.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhhmrhr.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2scobrbcp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpcaqdm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxaqpyi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeedqyp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2indbdbck.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvkfftk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcbkyeh.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnduszb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfpcije.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcemznx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtwjrbr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtptewnz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjadrnyi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyvwtym.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uswnzxep.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrlxngu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mknxncho.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbhhcfa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsjpgiq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeyqwya.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cazyspcm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvjpsdf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzfxduj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2surbtroe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qupbotkw.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyoojlw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzureps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjohyid.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2veohblrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcfxnna.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hudjfzxl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqckmvqt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fykvnzlm.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnwfeiz.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zfklwxwi.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wblttpoj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jnubapvs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epgrooin.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzjmpin.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reciekar.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apjdzlin.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxbctvn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxtxfvw.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzuhqxm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxmcrwi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfotxdpf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2henvbqmx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2esgmtguv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oplkyfjj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jzydegsp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pegsqdil.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lchdohop.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxujxipj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rezwdpns.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cykysnra.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpmfrdg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmklpywr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcylxlv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2todrxanx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiyvtfm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vulsfbbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoonghl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rllemgdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djndqqwa.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrbqjoc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgjbyfl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2anokrdma.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaxhxnl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zucdaxvi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsbmcbl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ammuzmhz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnfwbxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuqtsqb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fowucolb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2favrttpa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgbpcvq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msqqzmrq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhppume.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwqloxo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkrvvtt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtffezw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sofzytbr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hadyuwky.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaxqpxj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiovjkk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2prhznhwn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlfndqx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcnbvaq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvlfyzc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2woecnmzs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cijnhsvh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfesdnqn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpijsiwn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgnawqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2klprsnke.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgarqlt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2uydayvtl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrascdd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrijqoe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjelhvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uuksqeqr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2eekxlfsr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qstpdokk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aszsrxdr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnfhyva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zokbypvz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpjxdge.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bksezkbr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpazdcjx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byofknai.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wblrydbq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndabiufc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xghfdiku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nerexztw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwmeflx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsaxwib.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpadnke.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuppbhz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxfkejx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkphcli.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqnseky.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bbciptxr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qikkglnx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qozwvwub.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvossrne.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhclsfd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlpkwsm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2buvnxijf.html


<!-- 参考信息 -->