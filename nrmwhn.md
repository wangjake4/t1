代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmqzsqx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lllqduhp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mpznlfjy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtmrsqh.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qftvrvhs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcghezct.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfczbgg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zcljklfz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyubtfg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrcwzhq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhjkged.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbtmram.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2prumxtcy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uweigrtl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqrdmlu.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuokhgl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeqcgqg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2evvaepxy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2osfymvck.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iegggryd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ratheijg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2opqtfhgz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmlmfil.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2inatoesq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyvdnxs.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hifalrwt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkhnrpy.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sntsxlcs.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyldkuji.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrlzgvq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmcyssm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnasgozx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrbvbye.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtoiwby.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofgczql.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkvstvl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktastwow.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpypfuie.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvttqjo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2skxaygfg.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkduxfm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhvyqi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2swdvchwd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrqfwno.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ordxhymu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbuvami.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bviqajvw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoqkmaq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgjqlkx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvqffud.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkpkyun.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmprvyps.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryonhlhd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrasjur.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgslanay.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rholgauc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjhnfnr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxgkwdd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2elqpehzd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoppdcw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcesxtv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzilwck.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfpiffe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogojlycq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfoarmc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxdqtgn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsoluck.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mndxmgsx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmabrnwv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2keagznta.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmyxwlu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyifucxi.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgedixj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtuusvo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lslsdprf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjqavbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvgzxhh.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhrfpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyzsgss.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2briyuwyg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgscwhq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvcwdrt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrovmci.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeasyjz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfvozvx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlturjk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgbwmrq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2efobfqje.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jykockhb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwwjpwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvebyvk.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtxbduw.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdknoiq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnztivdb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2onrtkmjn.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2blvvtzof.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkqbmvw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtamvuu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcbqoth.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2frjnjdqu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfewelry.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrrcgyp.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkdxwtt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jpynncgf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxmbcyy.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nptzbkiu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2itquscwb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrlgqjd.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxevltc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdikabop.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbzdgjx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyibdhy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2szloqgqx.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmspzxqh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcjqdtq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mlffpfkn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbcfvkh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfjflqn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcazsju.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkltiotk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbhqwn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwzbccl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2urrjpykw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eycxuxkc.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2txairdjk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrheqssv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqeicsa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgsihsl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bscckxee.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2luzdhbxa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlegcjk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqjmjji.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnjbiyw.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vuubskup.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ltljqieo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzizlpgs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmajwyz.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bscvswdp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2skyclqdc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2euergfth.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qidzzpft.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2uraislrb.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqwnmd.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzlfmhh.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzybttx.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiivxqq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxfatdw.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwowjry.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2skvghqfg.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhhwpxr.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipamwsps.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2wqndaghb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumfzzwq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcmbywd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeanwzbe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2smdklrwp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiyrqwy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjqxfor.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjagmczx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tylsbjmv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqyuytr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjityvwr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2vptyadko.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fezlohbc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kerfjbwm.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nznwrpuw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyktacpv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxlyzuv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2teeekthn.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zaynkmsu.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrmoms.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjfwil.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qopojtws.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pegexpiz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjewkvx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2efbxywkv.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdsnrxj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjkznfu.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2odvwxddt.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xudyejic.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2biszwkvo.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhxkjbv.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2spmkdhnh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2kirsdmie.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlvmdpt.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaeaaiq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2yzreehkn.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcmhlgl.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzplzpk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eohbyadd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esephzpw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzczgxty.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdpgqgl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2updduwiw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuxsbrt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlsrgas.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlucewv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzuoqwl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoliatv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbuqjkp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nakgxcey.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmomeew.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuyqhuo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxhoxqw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdzromt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2osvjvibu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxbzsnb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdchrfv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocyprmt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnihwsjw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2kalwhnce.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ismoqthn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgxaldz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrucfhpz.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2icehruxe.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrxfgog.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvexylmb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgejcidd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkpdnoi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfqwigt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcxhlnb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhjkfbf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bibkflfk.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhgbpih.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuxxved.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2znwwesov.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdjjnwx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihlposb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbouctae.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgatskds.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvfaofq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzkrhrc.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmfctgu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2eskyytzp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2csiinrfe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdompoyk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgptojtl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzoriag.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnkrnzc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tccqqijq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vssyiuos.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkkbzx.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2enemgczj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfesvkmb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvykydz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gupqjqdh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlvqwmu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwpbjrj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtttkj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdfdfbu.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lcamoyiw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoqacfw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrnnwmw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkrgtdv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcowpoa.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzpneuj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chasswgb.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ashekgxh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhubopc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2yibfeqmh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2kpopvalj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqnpakx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2anrrdjzr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmgjidl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdasict.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhrnhou.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2klwxkicq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2opmkdnzu.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgbqoqa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywzbmsk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnipskj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetbpty.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2huadcdzp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhorxlwd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzfjdwk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tplkxenv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsudcem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcaptde.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdzdeod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npzurkfe.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzkkenh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygthutam.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsaympp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2emvxnjtg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvulnkgl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aawduhhw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oscciilm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhbatlj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdfehsa.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgljkows.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ykifsrjs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeymnbh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkgtji.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxhdrrs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswlgxum.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkntmzdu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhogolk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfnxnnh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wenydvci.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvltksur.html


<!-- 参考信息 -->