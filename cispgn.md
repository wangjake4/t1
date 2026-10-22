代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvifnrr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfksshf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcrhmjy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2unyjxusg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyxesoz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2lggvotdb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugfhlha.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kndhzwau.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwlhoma.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzfabrh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qktfyaaa.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpcgfmi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepqalu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2mumcpjwt.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bngpezvu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbhackp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxljapsu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmksdqyk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bztikrrx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkurxpvj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayccdrwv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfqzrfp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlyfjbp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qzreayxr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaqyeej.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxofhhu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfttyadv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhxghcc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2djcatigd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2acvskceh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jhodwieg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuflnvc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ayappouh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hepoipxz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fualvnnp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbnctda.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgotnfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2yunivkef.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwdczcw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqhpsqc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ofucokqe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2eflrhyxe.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojnxwsi.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqiwqvi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yhivsixi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2azteqpic.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwchctnt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dbweurnn.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vdemivhq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrovkcb.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tscanxjz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2omcymvul.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuyytti.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcnnznh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqojqxg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfkmqdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfpuhbq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2phhhexjs.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpquagal.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2czurrmgj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgwtmkd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ljymuhax.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogyahcl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvbozez.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iavuvods.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsonied.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2svbrqgun.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2finklgys.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrdjedk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbidqqog.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2amzzhtwh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwiqzyr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2thtfksvg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnrkde.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjepvbl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2inhqfydi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2znpmqbaf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwmxerr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqapqypk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxjyisv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drimyxcd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rswzaxzd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nojqmvkh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gusrylev.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoqeccv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2knvpkmfn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpiwtwy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtibxvax.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2btwrrrif.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaajtxxm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwtvyaz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyedtgw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjbtehm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2efgwonxs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvhfwli.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqkovop.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnkcmer.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxgacdy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkigxewm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyedzli.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2msaxrhwl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fljfqjgl.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmwunik.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrncpnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxalcaei.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvxppul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2muxtjbrm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuclhdf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcdcdmx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhauqqb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzfwido.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdplrvep.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxccmxa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2loykiris.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkveldb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2chfmraii.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwmdsvh.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2avtbutgj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkznmek.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpfenxo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtindkld.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvijwnd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoeiyul.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgquuqc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2obpozaou.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ervewugu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkgunh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyraikq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2suegonlf.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbtvqpw.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvslisps.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrndrsp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2robmridu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmyscpr.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhdakio.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxydbfau.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2songxwqj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyfveih.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2chqiuwge.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqubnbld.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpvqofw.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceejqqoh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdmqyce.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqqjzkv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmynzrw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxuomzn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ladhuvxn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxazjbt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnpdmxy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmotodot.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbsoomo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoojdls.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zznhfqau.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfcwzpr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rshmxpos.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjdqxqc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2loazuuss.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuauydc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzkhgyc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2buzofozf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwptjakt.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gogcowku.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2xhonybgf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2thgkdwqo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gizrgmcp.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2achueizu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwnyaqt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlsrcrg.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsrurhe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjecdzo.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iaconhqr.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vurnkpgl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvipbjuq.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyomnevk.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2igifjimj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2akrvdmls.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyqclea.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pznghkbk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfqyvpf.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2qedmgsny.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkskyazh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cltjdcvc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybssgcik.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgzffry.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixusjhyv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sljcjjxr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lddhnewe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfifuoqw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvymfyl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2npbztqyy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdfodtm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqzupwf.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2irbrpfgh.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjvoiez.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2oefmcljm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjwnkjx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdfjzyq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoctroc.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2balmhmzz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjybkn.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxxtznv.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllskkr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxurwqma.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2aioessjl.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pzguyxis.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxbrwre.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeqrlxu.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxcsnh.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqypwnur.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvxvebx.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uklyzlaj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2spkadahp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpfxmva.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2evckafms.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlmodmg.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuqvrvs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszfeqrn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkoyfab.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2somphyhj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqhfhiu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2suzcozpf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkoucjx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2thchxmwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijyjts.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdvqdbe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfiiwsm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqztiug.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhgqmfs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrtycsy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrvffhd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmuklqz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqmmtjp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2oliwduqo.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2styqsdea.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpinkdgt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiylkxxy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajqqipl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtpdebj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaqfdis.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyhqktl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjjxnwi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thpkisss.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ualoxlyw.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxxpfxp.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2sareapie.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2euwwmwer.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhkidjn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pesjyxuv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uzavutqh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yiijoigk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfhhlai.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnvflvv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwykvlql.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wosfgjsu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwxolzp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2schtoais.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxnsfon.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfjtvwz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2xovqxaba.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzselml.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2imdhqwqm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhrilqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhkgxrc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdycpero.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2azqeuryv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqyphpx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkoevku.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scawaays.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbownra.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2raxipbjh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvyqgbx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcjgoxk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnksnoqu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwxonxj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwjnvcw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2knuhqkrr.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xidyglkw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwdmwzn.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2arrjpzfy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jrigjofr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgwlldg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsegqtdi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzpjekz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpeqlao.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baesgxlo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdwocmh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkvhpsp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2stqbucpi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2hfifjekz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoenzis.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfhdedd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kfojnfrs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jogwdqxg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiojffu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2syyxcqrk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxsacqb.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bcllnwjy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicstdeq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkktfiiy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2prtjcacm.html


<!-- 参考信息 -->