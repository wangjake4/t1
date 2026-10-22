代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2naetlacc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpsvggp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aeikijgy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nualzkhp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiqsqvi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzuyqwo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlbcifw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rktduxgr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2olworfma.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxxkeam.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2prdeqhis.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjwimex.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdphkzm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2avyemyhi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2akfrmrpo.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvbxqdd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kloelyjd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfocole.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dyscngwk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrnexwc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ylybsokv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2twztoipo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nenefrxl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ruequlfh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkedgcxp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuzctkp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qdduceim.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eruwejjm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2prqqzwca.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqmpwib.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbsfvhj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbwgkvn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qnztfged.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcbpibr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cltdozei.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mpifyxra.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtweod.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qbytxlsk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvspatk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqvojsm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpvkhfn.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsorwveg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cybysrmf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhqlsri.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpnivlu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuovdvi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvhhhgf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdrwkgi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyiqprf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jyayljfa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvrsgzk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjamayw.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmoyrjd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaonlgr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2cyateoqe.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2axfdnqzv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2aimhynyg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vexqqxzi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufizlbvs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgyisgl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kadzhlau.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqdedfc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsffmigh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2bdquisps.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrbntdy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkdeott.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbykhfn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdxmexd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wivezccv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jalspulg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkhlevr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuzducx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2azdensut.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwamapeg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2thuayqyj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksytbcpv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbquaxx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgdvppu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsrvjmg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnxawen.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeprbqi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiluhkv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtmkwrr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzvkbtq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2brjkurnp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qixgvvsy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmadybb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgvppjp.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2svkxgbkv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gprxxvyk.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2opofdpuw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbztcjud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmftgoxq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrdwizc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vomlnggf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgufaid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaskpfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyrbeyf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfosqzso.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyswzycc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjitqnki.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnfsnyi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mgznmbyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sktmjcmp.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnakrntt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdahmpn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtgazkb.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpcpvlf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxswhzyi.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xquftdsx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmujgelb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jddzvkio.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzyrvrc.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zijygzuu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwentrsl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eudrbeyv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2idguhyvc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiwecvq.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdragau.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kojarkrc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnamrjxe.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oongcwtt.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvuebsd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lquvuima.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyymvkjy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsrqfcl.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcttuke.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkgeqpg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pudhshjb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ascfgndb.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nolkmqlt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sctfcztr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mchrmlkp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpigcwg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lacpyizw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpamcsa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmxastl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtxwont.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mivdhkcp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqerbumj.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrugwzn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvodjetz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdtvybt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rawzyays.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yubgcsbz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcwrrpr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmcjyjb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2maffnbuu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajysjrwh.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rojpazxu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaablht.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2clyiztdv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfigyheu.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqtajti.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2brnjfrxv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndefblvf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xekhvoef.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpkcpdc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wjizisrz.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwjenfw.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnftrse.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjyenzb.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpwsbwl.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eccsfjlv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2krzwllnj.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaltawc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2angdgtmi.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hniwfxtw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojqdotc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mivnooua.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gssuzwre.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxndsvu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2quydpath.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbrrzmw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xszuyfyi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dltisbbi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2mmptnbdm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxtjsb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtbbdax.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aidevfhh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjkkyld.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhsohyx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxncgpmt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzieqvw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlkhnah.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrhstwm.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2woswluwq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2atioozuk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxndptir.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkvgzlv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbfxmlw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2etwlbfyh.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nirqhfgx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2urcyxhtz.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlnoiis.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpejeewc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgonovv.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fbldfadu.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcltvp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2axaenfar.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjoxrqw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeibamd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoyccqu.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsfchfm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2grprvfja.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ranoagpq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nubfikqs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxbyzas.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdeditq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqanwx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2rinngfzb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovazte.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kknfwqph.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2huaacqrt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2isrgkzlt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2oistsnws.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsajuaal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaxdalm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2qasfodmq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tutljykt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyukgyt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbexkbqe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhxbidl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohagaxtx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szhewjxz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjrineg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsqohck.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrxairf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjauqdt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdybplt.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnyhnan.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpntmtiu.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyozdmnp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqvajfz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxikqhkh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2savwfast.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zprptgex.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbuxjh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgsrsjm.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnfimym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpifmtf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzwvpcr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgdtqma.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzjyktb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnudyeu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrdcxxk.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2izdpnzbp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxrexnh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2abdayasx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfdsgeh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxgdgfm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbuhejj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqelkzzf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjwtmdy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oasyynbv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyddnlhr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agmwouws.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnfanbf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdepormz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbpdyad.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqvvnxg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkchnidg.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxepqecl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iypabzwq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpdoawe.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nvybtfvs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgtwtal.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjkykbu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrjqcvf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vumdhlke.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaddlur.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjjmvoq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vutabagv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxoyrdz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcdguhj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbiutja.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgtgvox.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2niorcllz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vprozham.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdrilkl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2laurjmkm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqgevwl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpiikad.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrajfoi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvnxtf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2afncblfh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uutkvmat.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2monebeok.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiefyxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2muzvzucd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2avxzvtmb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcbkaca.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkhivss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exntlffa.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrvjcbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaizzgy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eimvycyp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2olrwqopx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvxggoj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtfpznf.html


<!-- 参考信息 -->