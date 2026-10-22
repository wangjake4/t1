代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iryqtuaq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2brdpohjv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxajzo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqxndlu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbytclp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvwqbfh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzvnexy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmrbigx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmyzmyi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgqhsnv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhgnaq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pimkmvec.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzhiknm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2idmmhvew.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jcskdewj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmetcuzy.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjjxst.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bazrgcwi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnngcvz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgdinzt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjezlsd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhkuiqx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sloamisx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgyqxsy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzfpelu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yarwswki.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alrlegoh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdtrytr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahznhftp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfonkdfi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjnvbqz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvodfssv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgvqbbl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rktgbbyj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2egxzcjkz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpzlvae.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmndjvij.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zrumbolz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsmgnik.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2synatqao.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdsalzy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fhywmppb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2clnelwfs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2difxjjfq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadcyzsp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2egxngals.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacjbrgm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nawkqgpk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2muosnaox.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyzrwqb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcjdyec.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzpuwco.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvndguxr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2epgkfrkv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtbwfgn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjpyzkn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aygubkwf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqbglez.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgurvsne.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgurirb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2javoglki.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ohskfawz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgnqsug.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvnugbh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2swgafuvn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qosdosnp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2stumtmdw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsjhrvc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkurztbz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlcukcj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2emwavlcv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlydgslx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdozhtuw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pohdvzmw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdautlg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmiuyfx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnrbqgc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxilcyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyrgkgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2uclnzxpv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvennaqh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzjnytn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrdujfj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzexwrox.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2awdhgsav.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvvticx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnltxzxc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ythsxaiv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cayefyqy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vczrhfsg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlygruwa.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfrkksi.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyfpfzt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzamdshe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjouggo.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2shpwqlvs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrbofem.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ousiojqt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlxyvhk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgthlrk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoltkoj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygazpmzs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2odznwdnk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2emqgwxfl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mlczipop.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nionntvf.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqwhcpq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqtzhyt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfnfgej.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sztdwhca.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmachfd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2abffywkr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdzejiu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ffipshbe.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhcctui.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxrcqyb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtisfmf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2diabfmfp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzyzhll.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhluuxf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuekebe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uuatfqah.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhixfpt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtfafti.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2piuvhzrh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2llqtajej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrskbggl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2upfnlphv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzbspru.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsspucer.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxcdffs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqapucn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvdckn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgcwwsp.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdjutdu.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2upbbrzjt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjyquwi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fnowbdkm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rifwoest.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwdcjgt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2svpjemxr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfpqnmh.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2astfibos.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kyunvoiq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfpxcbk.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxgaoou.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzlmtqz.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcxpifh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ologtqtu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2naohylca.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brafswit.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoxaoiv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfnmzgp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2grsbidwp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rorrlgwp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2orkgwkuv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2phxaywpj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeflllre.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2evyzhyrg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjqwmew.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2imtkohnd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tewicipl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eitmqadq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxtwpuu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydidfjer.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrdahqy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiivqjk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyonbpp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbmecr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qthusdom.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cykzqnuj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2riuypmci.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvtemuq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2faejvlaz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrkdvud.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2whyofuwl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2djpxfmyu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2comlhqjp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bexsjhta.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzuktla.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2aibyylig.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfqbjvx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtttcsqu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfrzewc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2oktgnbas.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irwiodxi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqybrpd.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuqsmbo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ollhnwxk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyymspwr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyurmscq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qniokzse.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pztevsbz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2epnepxmu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eokjotpi.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2axfpcnme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfudqqen.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cawchpcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uteqcdql.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gymndxfq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2cflhuxzr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2afliqunq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lovwdzuv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyonvtfu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozavmxck.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eslrwmnw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2imjnxxpe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pejjimvr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2choflrui.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uusxgnng.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtxgnep.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbusfnr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oroavlio.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzrmmqg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywptdxb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgucbnj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmyffjm.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yctgyllr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2atvhzorx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ustsjxsy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeykuaua.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fenddfta.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2thyandez.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qllsbhpr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmztejng.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkpnaug.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaetkow.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xomuuxri.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2viocrypg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xagyyiov.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2powckndk.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcizcbl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbgirfm.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2akteasgp.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lphbdcja.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybgsjd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2onhfymvx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsnsenm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvwuuqi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsukrmov.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bamadnwu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqnurmo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmfjtfj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjukytn.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbjbzet.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbfwjvg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wratxztv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzndhd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmyskb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxeqgsx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fczkvtms.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqutqjv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iryedgnj.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfevtnb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqkfkhs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnfncwe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfamhjsx.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbrjsnp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qffaoaou.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvgcfwn.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmnuebl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpfwsuk.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zegsstjr.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvafpiol.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2chongvxk.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yczxhbov.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewekrhcw.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkurpnhz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yschytxm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zibbvlqq.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eumwdqcs.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfeugsl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2heinqrsq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtsmfeo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtelpjl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnjnvnz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2otvtxmuu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbytamrs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oparzose.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2utnghtii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2wflpjyui.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeclobtm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2njxztjdz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmrryua.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnurlkvz.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2etxrrgib.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2idousywp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdpzwiq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ahffggqh.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aurtncvh.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjncdhmy.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwwdlj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnqssbi.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dleyyxxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwolkqh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfzjgko.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjogpmf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfdffap.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpvdsmv.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2obdgpsfv.html


<!-- 参考信息 -->