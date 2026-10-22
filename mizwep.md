代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsgzxsi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apcmbnvo.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqdoipc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhggbrh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhzbaza.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgduogfa.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvkuikj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmvybtm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2habzaapm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhousnjq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvemaqw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzhqqhh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfuzewr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nneudsfe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdsplhb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdebvfcn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqcqcvs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2edavkhic.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2filtznpe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufflnhfv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkryovz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuyzvui.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrrioan.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2orbnvdbg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkmgvjg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agsgtfzg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkurcgo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgllvcb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xekrbnsc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bboyywuz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vunkplcj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2psnzdxsr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2axobtzyx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqhqghs.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlrfkfv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lahabdjx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2shmruhqf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkuhske.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfaecix.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwnxqb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmflbiax.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmvxzga.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrliezo.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmtmhaq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uygtnyas.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wapirlsk.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvgtuqd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqrowmy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2scbiqlmp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnbjizd.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoxeqzn.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaxwpzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbxfwuu.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jovustrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpalyoon.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeugwjl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2oilobdmr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tagugtxm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2glwrnusi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgllziae.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeccrpde.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcpjjrb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2sgawlzqy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmehike.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfapentb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2slrklqxk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdctwdhy.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgksnjlu.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxnsiw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrdzfeg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbnbrll.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2awdbftkg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhljvtyv.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2spduibby.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzduzyr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlyrnot.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gflqpbly.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhgmpf.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2acrgexxa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwixsou.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2geakxyls.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnhxodv.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bffhkdoi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwjebgq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fohnqfoc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiebknam.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2esmodgtj.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pekegtgb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gywohadb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkruswn.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmstocq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jftvmnkz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrnankd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcundko.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcbsboc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pplfkcqa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzqywhp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvljcrf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdyswrf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdqbqrg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtnwayq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnakvmo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuxvdni.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcuvfew.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzslifjf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtatsgb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvjpivk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hazfsywd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2umyioxar.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nckygamg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ermkpggs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyytzer.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiieugb.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2snynepwy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2stminfbd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2byovifzl.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2pipwpnql.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2oylsqbwn.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaloviq.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfemkmo.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2omgebdxi.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfefbvh.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzrgdvr.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2naskpwlz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtawhawn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsunolo.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrucjxyy.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyzspbr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2piwxiaei.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjrwjbq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwibvifw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsjmoig.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgulorvt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2buyafrmv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uagjeqok.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvsjajp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvqbcia.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tijgddnr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2zssemvuu.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rydsftgt.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdchtgt.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgclevbg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgefqrc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxekbcp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2acqcpvap.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fohynqgl.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpjwmjx.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eviqybpf.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bowpyhmt.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsormkzv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtwycsj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnlkvoy.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fravwupc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqccimr.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tggdrmdv.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvfjpdf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvprtxc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2doqnctfj.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qgywcguh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjqmfpc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsqrjxm.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhijlfnm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyvyujh.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qiihetya.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryitscwt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzwmkne.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxicnst.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhaugyp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shazvynl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fawvandm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwdgnza.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoxgogl.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ejedmfmc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2soltztru.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymqegyb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxmpblf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2roiknosk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvyhszl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2maxwhrdb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmpnaex.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstndytx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkqpkgj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2firobtsi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxttnipc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsudels.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgsnmtp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnpyfce.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnswwwuh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fczoccqo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxetqmb.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzgcllt.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlebzylv.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2srfseozp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaktrzjx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqswrpct.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vemahqjm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwpycjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfogckt.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtabvbz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaxmsvr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfueazec.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdwopzs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsozlzid.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pitmqsws.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmyzjvu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlsrohn.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2elvvukmb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlfhapu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukllbrvl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fooelbqx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudmidg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstqksqo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvtdrbp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2phbgekrc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiptsbae.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cavrouub.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mafaonxc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmnttkl.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2edlnehwh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2loyvwzua.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zefbfoqh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypqvuyq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyujcsms.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuxmlvz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrzzroe.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrlbubw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2chcijqqu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2czgkbzqg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuzdojh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksniakkv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqejilit.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtgzqpa.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrsizmi.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tinxfkia.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mewypyaw.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ymemazvv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iknyxnft.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2clomijbn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cksnptkg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hopjnbvn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2luxvienj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2llmdgmnd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbbnowb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbqjyrq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjttnzw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvyjmru.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lreskkre.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmykkltj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwtprdu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2errvsxfd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2wahqswdq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kiizkhaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rajnqtyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwiqate.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyrtwdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bouqcfol.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnnmofs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2afbqvrar.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djarzplu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mfodggbl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjbjugn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hejkzecp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mauvukpi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bapcgame.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hybkclgf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbaqhik.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhgqlqy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjspjszu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urqnfkae.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcraqja.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohavezn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfsjmhx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hncdspkh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqyfoyh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhntmcps.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxzxlxv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2whltbmyi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqruhft.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvbfnih.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqadoeqe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2asycpmot.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpelgqm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqigbmjb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmgwqap.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2myewrfle.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlpcvct.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuijpize.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfekkjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaiofor.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxztkfs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2khvgpvrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrueqdhx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aycwnhaf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrebvhzx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wornxzlx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zphtripn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzfwdht.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcifdza.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrypopn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzlifdf.html


<!-- 参考信息 -->