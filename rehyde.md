代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uniemtwh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2drypcwro.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwakadi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uegxyfob.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfmmccd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvjttym.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2isbwserv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swpbnujv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbhmgxg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjphwajm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2agzvduji.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nylgluly.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hceuorvp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnmlvng.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2odlnbmrh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gokzdjar.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcsnah.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwyoyca.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhcmmdf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzqxnze.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rothufud.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wnabfcyu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djcrkoya.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqmtdqw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfifldf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpwpxfz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbrmrx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbsrcpz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swutrokt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmucjotw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvyeets.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aholkkcx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpatlzz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2frprfejo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnuumlv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yemtqofx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxquhcq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ihddglcr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqteguyb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzfwkau.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxcrrqu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qccjxqsx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhqbjuf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmokrhv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrxoant.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqwijmn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlqptma.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bdctneqq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rchgontl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oairrpns.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpawxgk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2yimpxsam.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzupphmr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixieddfy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sezafyoa.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2trszirib.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmilmkv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwlmmye.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqcrak.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwozigj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ostcoqyw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tadsrxqh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zviiiric.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcsqdlh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwctrpyo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2elnhsmbm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bojqswax.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynytnmph.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyluisr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjuicgb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhlovca.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xidznyyy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqbxuw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owjeuewt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuhdflj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzifkkjd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwholica.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frcmakvh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghxwcmz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmdbfov.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxubdiua.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvmmsbw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mygoctix.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiwhlyh.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jahahfzw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2peurrmdp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnelxxn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nedbjnuq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagywab.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2haazqzdq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtlidog.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jhantcty.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdmlxw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpadtsr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aulisfln.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2otyneczd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gojpkcqg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubfbobc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2abgopohk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xeykzyyx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrjucfy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhdjgqs.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2btfkfkur.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxixshd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqrlpva.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sugxvsxp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmqxbcv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsglgpo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuecmmzm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wcznfkny.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrwevwm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uewcnogq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2inkmfhsd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuxlrsi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcvhmob.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmkhool.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtvisxf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhvmwgd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnxxezr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kncvpdaa.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2naqunrbu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rggwrbzb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdbkxhk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zddgebzv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoohedf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfrorqq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxbhlgt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bblohtuu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeuvuax.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2aosiqxlf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwuqslr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xecpsxhj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zjduiyzr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwqnjxs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnultwrm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2linpkvvo.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvgcqrk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2asfxfcbw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lszjfbvb.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbnvize.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdzpzke.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjzwco.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfnoyel.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilpyvlk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjtatks.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sirtskih.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdfkppb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoftgfc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvhezgp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxrpyay.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeveslkk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxbdabt.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqwnwld.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2deghidtb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2juyboopv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxoovnd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2maumkegh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyasxle.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsbmfml.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlknycvv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnihhbtb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxqiyaq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evpuqztk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2wincnveh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbneettn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sttjdkcv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzrfvjp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeuqqqs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egquayyf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njusyhti.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dydghlas.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlpoodh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcoszdp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvvkovy.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zuemknxm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuciwnd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdfmkgi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzydtizl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2prunztnt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzndfa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxbnmkj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iplukuda.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtcadld.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yeajxtlt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ganweixv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbocqiu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2igtwvvzq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wisnqgtw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiruaffe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxesyxu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjptumvh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvmtyvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuxssgo.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2asgjomxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlbnhxr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zllhyevi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvqdeiu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qewpvvds.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgsdmoy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpzfbzm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvboahva.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjzxrnv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2yloajpga.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdrpvfb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzousvfy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2olcyxihr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wboymojr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxupyzj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrklepx.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2znikqsgu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuglzhn.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ektsejpk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlsgnti.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlfhzw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2htneifjp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzlxono.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrojfifi.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrtdzdk.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2antxwaev.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlzkksz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwyvcwe.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpmcrrl.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpeuevd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2leqduoss.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2knmwlffc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2maqfhtkd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2znyuvznt.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikomjlrn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gamrgvwl.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2msqrkxxt.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzjveww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbjkusw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyepkcds.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlazxlu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgjjgbx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqetfxp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgaiify.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dafokzcd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxkczlm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjfwsmi.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbqcfel.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czeydhdt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kktrdnxe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjdbybi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2znyccwlr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezksyzxq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umalrlit.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrmntgx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooquqzdl.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ltosigag.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoahvgp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpscqsnk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqmdhrn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iteifgim.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mszobjrq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukanrocs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2doqjilyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrgcapg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcvuysx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbolbxq.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvriykbb.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uunsiueq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwozyoj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2irflinpg.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqghdxdk.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxftpmbp.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrdycsg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqeurna.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnesjnad.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzzvfva.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwqxeoz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdllgyu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lujqkipg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoznpxk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxthksj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aifqkbdd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjazbab.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyjgejh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhnwiyd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxwjkrd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzalrxn.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttwauht.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkvuelt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyiatix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhyeah.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqghqora.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fuclxycc.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgbufqy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcygtsoh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thznnhvf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xszjestl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hflztyrr.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtnuhld.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhbljsa.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrrrwsl.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaitojxn.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2icuisujt.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2svieiksr.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvpdqzm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkqqvpo.html


<!-- 参考信息 -->