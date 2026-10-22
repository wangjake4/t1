代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuklfbj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xggjadat.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mspqzttu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sihbognn.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fyctuiab.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pznnaahv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhbetww.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsnrhfd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrpcnmw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdapbpbw.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhepqsbj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjaahcd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjcqhc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjumuykq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfawlvz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldjsfz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szkdaaud.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vdckhscp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2efebpdbr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwxltti.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2evqhamsd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgslzibh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2exzvusvo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2opdnjryo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjsksyc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbeddga.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vunneacm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqjeytm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvtntxq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bztvkteh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vnadjyrm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmldmdf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuydeatl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjknjxv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmplhgt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqamkpum.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bunfjxai.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2suxcseir.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfwmmml.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrxwmtp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tybagqnf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmvkcmw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkzvhur.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdbubxg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdjtjyg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeievfk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdzcqdj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sflbggwl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmjylii.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dykyjoji.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sphvcrga.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tyayrime.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2onniftfg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cougjmdp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpjzqcm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynulemwa.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrabwni.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2efzmaais.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tazzwehw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkpmwsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trwearfr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yegwduex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msowiwmg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2coasagpt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxopnya.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnzvgjw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbskbjv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzfauzs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnqdlwy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2imhqunun.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2rxomwdvf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqqhgmx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zghckoyn.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjzuyiw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qquhixli.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunknvkp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdabbvv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqatlto.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnivbyh.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtsinrf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvsgpoz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2irdmkfnt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2loairlrl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntglkqki.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppkkmge.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtbpcie.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xohlvqyl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrwmyop.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvoehvl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsuaxcn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdmgyzi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dagzwxny.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2sudjskkr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2twlbkrwb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlijgmue.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmacaun.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaiirgi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyquehie.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zowenzaz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmmssqr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2atrieleu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2djxajsca.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2btziwnyz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnadhuj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlvizks.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yirirvmv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kntstpoz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrezjcts.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpchrngl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocytsmxf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksymkjif.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfgnext.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2imgmlufu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmigtoq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoldjkh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzkncn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2doagbdte.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpobife.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2adytjwrx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxsysac.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxolhfi.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgcphzu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvwvyue.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmffysb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwvakhb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2munrxjap.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fndikcya.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqhjrsx.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2coaxiltw.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmhwlbo.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkibvoef.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgytdwru.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sofdtbrs.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpkohdk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ullmgawz.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwjjswb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqkyogc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiknzim.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2juhbquvo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwawwddf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvusjkcs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxxkkri.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqjgqkx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vokgavrr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2stfubcmt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zybvijoj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2rddhtopy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbnzfxd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjwcbvp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaozlqo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbzndxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kguhtddx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2tfssvbpo.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxwfjv.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjgcidc.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrlmhru.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufywxyno.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndomfhes.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyfwvpa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2eifyrjwh.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ifujfcpz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zmakrokd.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsgmose.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmtrugm.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyulvafd.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxzhfjn.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdkifdj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2puqsvsle.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fualmael.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2butifjoq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2pddxfdog.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngznkzts.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcjovcx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzyowdy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owanvnbf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzomgoy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhprpoj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2muqjzopg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpklfsxd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiauszn.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rntusple.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvszpea.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhonivy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlhxalo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjtxjif.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhegvidz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijddxzmw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsierhx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzplkca.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwgojq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orlsestf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnjwrec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkojene.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hcslopzo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zjszmpha.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oriivieh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqpzwzb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2senztrrx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2azrzlkoa.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifctyush.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2dskapguw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2snuwbeuc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gchlpcux.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulawvrl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzxnalq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2svhteyhv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwfgzov.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2iexgsraj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2onayvwed.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwciwfuq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chkballq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxheazp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rogpbtfv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yizhyqeu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2sqohceaz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgbsuts.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmysztq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlidqusb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2quyoabgv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsfxmxw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2caeqbhuw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeweiak.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tshpafey.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gowfzwyi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okhgpbya.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaeluqn.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcgslra.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujblxarf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsrzmfu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzshnwl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqusszo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrfszkk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2aycantcf.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcecpol.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2sazqtnfj.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiqrgyx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kwovzfae.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsvmysi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnycqkxi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaucdqdo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrroiuw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2phugdqnp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbvnaty.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuygwkh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2osdbzmfw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooebpuih.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbdskgl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mxquumew.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvskkcg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoxmnjr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywhpbi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2atvoejxd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpbpjhg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eezylgvn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvuurtb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opbucywd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpsjwub.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdedfjm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dduwczul.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gprnxotz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfnefbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cosdjvgy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2durtftsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqcjwek.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saxkymnm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzpopzh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdhnsyx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbhzcbf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmariyev.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2twxflmik.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wjutduqt.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snudkace.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2smcizhug.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trbfofta.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlpskno.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzcgcvb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyuijlx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkuhgdt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlvvyqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2muuswjah.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cniisfde.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoqofmp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xouzoszf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdetvgrp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjrttgx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lonrejda.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgptvda.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2owgioopz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bktzcoix.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnngcpn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2awaguxoq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llugewvd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2snswmdxg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncytcbfp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxubodo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgxintj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fupdvqqo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uarxpyxh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyynlbpf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyrcyun.html


<!-- 参考信息 -->