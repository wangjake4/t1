代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpdcsig.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbvwonh.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvixjaqi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwxwmmg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2glpfqzcj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhppslfi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cymcfrdr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlqlaek.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnlnsfj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2coueakyy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzifqd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgkovgg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqegoct.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2oizmqhav.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkdzfto.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgulxmm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dolmozmw.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2surblsfs.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqxanyz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiqwdgu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeopmpe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2budjsnil.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2urmefadx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2oslcmqdn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodxdiqd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjodtyd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvoghuu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvrebah.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmetuxz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2musgpcgl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyauxpi.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrbfvjy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdugldw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2szcqsjfj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdhnigm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2maracolm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xlztucdr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpjavvd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2momewjug.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtwuivn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmvqubc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtkmaer.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2joahatwi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpriewk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utcstegj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2elzejwkq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afensigr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nijpchfp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqotzrnt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkneaox.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdgiaac.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2etmrvrzq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gziotvhv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktcifig.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2gooqxstz.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zanbznib.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgbkqgw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2isyvpvxc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fttckufb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfryaja.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryllumju.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysocdmbo.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2orsjtppw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2mcemrhzw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryexpdzx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uocqbljg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2juoplyds.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2silaxxfw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwkgvya.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozaafjy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzroqbe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hroklpgm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdldubpo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2evhrxypa.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2mabnbvep.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kksknyri.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2flfqkvxf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gescxcum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjfacav.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmndovj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqumojs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifukbmt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdtexvf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymebqebp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocimrfkq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snviqbhv.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkgmega.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvjbufq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2unbmfppz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylneoeas.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvabsych.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzzdisv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzvnyhg.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pztjozxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxvfdfk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytppiidk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfqylnm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzflbwwk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgfwgvm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoeirss.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2icomfseb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtlhezf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpxeoap.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsyscww.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aexabddh.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqvikqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avzriqnm.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jatnxlez.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjdurqp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bulneifz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpifnvn.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdpqppy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2khmwulrt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkknxuc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgghmbk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdovjwuz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2piyeuxqs.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gahpgebg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmqgzme.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2otfhnoyy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dxefgopc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2diivctxk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2smowhlhm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnxgbsp.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtqkpcg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jncxlidm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkyuuuc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2auyymdlp.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkychgr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzsyfjw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtuajxg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbqdltu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwphmfaw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvqylfk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oowvtruv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlzgntt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kobdqvup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yosrtrzn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxntnytx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjxzrqz.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvkxshf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veziniet.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cubmhdrz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tykzsahw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoehlkd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pduwmnoz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcfpglo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsjvyua.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsufwfzk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qphtgwjv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2chymniic.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfigapa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bphkokjc.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrobasp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuikmrh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffslfzht.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcezruq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdetedxk.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbpyefn.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzxzko.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2szbnfebi.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fartbtvq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mucsieyb.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsnamcx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zadgzvhy.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsibitk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwxhlky.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuionyf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyacbwo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nybbngpr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2szfvhlny.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2devraozs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvfcxyz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwkgaez.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfvvzhl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhmvmtq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2xenhizoi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iblnaygf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2spomlvbm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywusmwku.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bltctkfa.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwirrmop.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiqujjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryasprdc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmwrssh.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdzbarc.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpjtbl.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoecuook.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhktlsec.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsosvyg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sialozrv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dekrmlbu.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hakmqrbl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzcfcir.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrldcifs.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2khhkxfgv.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2apgkqtpa.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2arwcycuo.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iksugeus.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2naymuuwf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2moajpmat.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2sezddbly.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2zzquskdv.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2legqztff.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlmobgl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyrsvsj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwhvfmv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhegqriv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxbfifz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbqmbrs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2pibjgran.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzitroys.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wchmsvmr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2rflgvbpi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjjubtz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fazapfin.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzfwchm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuczkbq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmbyaev.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojixobkq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtclqlei.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2usjezhpt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2spybipxn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueobyrlw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeluipk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkusgui.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wwouykbt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyafzir.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaejeszu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gspunzdu.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqhgdfd.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmewqolv.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2oemvcpna.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjloqshp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2vboisipb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypprzuhp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jahkqxny.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyjlhlc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvfwowq.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ginabvgv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtovtwru.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtggtto.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnfkijz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhpfqfy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiflcox.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xksmoobq.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uruvkowm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsbruwh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdlkiod.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvymhzvp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwhgctk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfrlalz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjluhsab.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxehgib.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjhnpfb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xiljgxrq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehioukea.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jqklbsif.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhnjxzt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuxxgix.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxssbpai.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aomuwuil.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmatzdyw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyusrczz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhhljek.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jjslrosy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2whtysmyj.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2logzzmfg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmdoci.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exztqvch.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhtoqth.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elihzokj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojubbz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtqnkth.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvnsfil.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmpylkd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ytklxuqk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqokuvqq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eudulcle.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmowpzy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmmmlg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxxneev.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ankzwtis.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dibfoytg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvgmhme.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcxjudu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2reiiedzl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrngkux.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpabyveu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfubnbit.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmgvlmz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwltstk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2whdumgct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2difcpgjp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqxifpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekngyete.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iiajlbrp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2apxjcjjj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhspgma.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gnygowhj.html


<!-- 参考信息 -->