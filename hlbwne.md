代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xubtisqr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bratcavc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdbvqoe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqkkoaz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2sbymripg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvcsaeb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaudkfk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmoydz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmenznlu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhowpug.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klkuoips.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyemvyzb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtelwpcx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqywyvo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqgiunr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrtnpyl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sugphvkt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgywmvl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2betqmqal.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvnpvvm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2juwuwspf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrxsyal.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2distfebl.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqqrpbs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxvsrnh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyngvnx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crynkpoo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2upobjfrf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2atlrskvg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjqmgnx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeekvupi.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2nulukbkc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwpkcaw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvbaksy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaaigkb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2romodblk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnzpqgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxalphw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvjdoay.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdhwoiu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xszycmfb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiweupo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqarloe.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gceygihy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nattuohl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcdpnuj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlkhxpq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2frqletif.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkufrig.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odqyrcav.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eauwtnrz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkhwqms.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2omzqwsym.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqcyuhm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyacpkja.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvldywg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphszxho.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qihtijbv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qieenbvn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzyyqzf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qatzzqzo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgisfss.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cobwscoy.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjuyhhp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrixpqa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqvdbkz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuujmhe.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlbqnxo.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ncforukk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xnutfekg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlnldbf.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpokvlk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvvqpyt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vctwzcbh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dclsubxb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjlgwsz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnsbojt.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egzshcsh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdwwdyd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2owhvtjks.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqzcaqn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbnftnm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxfjslf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vntfqsas.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fylhquxx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlptnjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbhuatu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sntkuvpd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2axozmbyo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyknzcz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpojmyvc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvmjcmo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2disdznok.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllfkdjf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqirvhqd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrawhvm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfvashq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oynqatnl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqjwqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpusenej.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywejvhaf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uivpjphr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmvoxpg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwqyqbw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfayonir.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkzhefs.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rncidqhu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2turgxhyc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjtswsp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mopwaqst.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmlxbhj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgembmg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvrlxag.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrpdsnp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amzsogeh.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2boemuytw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfxwtet.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoqdjzf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtcdqih.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwubtupy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wddtihqb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiimqhx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifumxlsw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyimdael.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roidukph.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lytaqxkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcikcos.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aharoeip.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrpnnxh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2swxvtrac.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2skzpxueq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2shftrvrx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbugabbc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmmkmqt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2perbziar.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2htgfvbgz.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdfmco.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkuanip.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2raupiwsb.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjixljsp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrqmwmo.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwojzlyw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbkzwoz.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgmxeew.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mupujcfe.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2klufexux.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xenuljjw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmjppnl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2makftczx.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmexzmu.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxotxxa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zafodntk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqszsrl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfzcwoc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkkagu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bauzlahp.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmauhwz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gssodafg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcesgiz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ampmxolk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rklqnnrb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiklsdd.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfyjnvd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgijudw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvedcftp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2rafmdzla.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaajhbf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kznusebu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfypmvsv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wztpexvm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2knylwvjr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxxfoat.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjpbrsv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgesawrq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizinvnv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrwplzj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nusardez.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuewikkn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpunpdlz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrqwfwg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjbhlyi.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbhmzzn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlcccjh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrfqyra.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxlolbt.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrbvohl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlewjkqs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhvzgzx.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdsmhea.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvspltjs.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwtdtev.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2usmgmbuq.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwehpav.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pclkpwja.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mywsuncs.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zppzrpvr.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2btiztxps.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrjqtph.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwzaxbp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2negfdieg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2peibmeki.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqxlxmo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2swomrerw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lchbuild.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuorxlp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlpfobn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wphhetxn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2luegsudr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkoifbs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kepibhcf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmnyabu.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqklurne.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzioxjjc.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeshwwp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvzavlf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhhkvyi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2awxdkssq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeezarb.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2obcngkja.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdduykc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhicgku.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpromkka.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ispeagmo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2olzzmavz.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvdarbt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhhoama.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2htngrcrz.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxeveqf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbifyrus.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eifdsipz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzertwft.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2qspiegxd.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsunryew.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjevulv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjtffjq.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfejlkj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxezsdkv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stxkdkzb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pusjwais.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zilpidjb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrorfmz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gflawglq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcmxyfm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vreinxtz.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzqderk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2iodrmxdx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eschplzt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimzlbdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxisimh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxehswi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2lydtdibu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuutnjq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpzouot.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxkqbfs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazicjsc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xozphlbq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlqobzz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2faaynfly.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwxdrgg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikizrii.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmcsuhn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpqadln.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2beavukte.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2seqpxtfv.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2plkdlhie.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2igthaiai.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdabdtl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uanudawy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jojusmyt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wnegolff.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiooowky.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2udwufskv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfpqayz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2myvxblop.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrobsia.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pflnnjwk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbihztp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkxemqs.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2dijmuwsa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzfhslv.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wktofemu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qndfoxga.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sklcdetp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcrztxj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoygtqe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqdnnlc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2riutvjpm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epuvermp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgwgojm.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyernyw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2lniloxok.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhibcaj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2czfxdqvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmxafgz.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgbzjtp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiidkphy.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlprfxs.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2aptyejak.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfulzdq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qbebpcca.html


<!-- 参考信息 -->