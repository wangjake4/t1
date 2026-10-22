代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlehmfu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtbgpbo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwaijqt.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmvfcvu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2holyfdgd.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrbgrot.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlojzn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ududzhxs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aisjqrot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ucapsppx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoxyezd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2biwseild.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qglhdweu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeshspx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhidgic.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zthvnsvv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izszfdzs.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2evvpsmrl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkczlyxh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eipvizpy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyopjzch.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlujhrc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaquuyn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamnofln.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vacexrsu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxqtaud.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqowkswm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2otanmzoi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sktrpqwj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pfawdkgk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nipvdxva.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhswkabs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzxmsrz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqtumof.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdjjihk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpvzrwx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xliijsvn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdppizxc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbrzypu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnpamjh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfvllht.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2glmojoup.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbvqgfj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2agvifrvm.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiyijaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbivbpm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzmioaa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgorbui.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhotipk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdnivil.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlttgnz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2agmhfwat.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcgiftm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2omftozyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdsinln.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gesfvxby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvnomjc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpsgxyx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkimxlqg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcbjqjc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngttpahp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2clrydfli.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uveyiegg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdtfefi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tynvmzeh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2opgqrisy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtuxqzd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2spbygafv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxkvnuj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2seumwriw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iggomxdk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxxaekh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyedfzks.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvidhyw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnypidj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqubjuxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wedfdezx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqqcmyw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvezdby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2effqiggy.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrvtfwu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykofhnhp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfxaprf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2clrfcxlq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxyvbxv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnpkbio.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kaurnkjk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwvimxg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqvxcea.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtvtrlf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsxkbwg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvzjfwv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpioqc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mruekhie.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqwfixw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ccguqnkm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pssowelo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnrwakj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhxgywb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtordlt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bekyfuny.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2neaahjia.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2suhomoay.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlbbtss.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuwnemx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtasmyx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpihott.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zygikkmp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrbspox.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2clihnxps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiraxbl.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2obyjnhpj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2agmofxyo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvoemvt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2itqxkbvv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pagvzazr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lpakzzga.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atkgozqe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujidqrcz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkhlskm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvvqkfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqogjzet.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzhexjo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uccjvmym.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaueavg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzbdlp.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvhsion.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2czkxkear.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vkppjglg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2alxvqnqy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmokdmjy.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mvftcrjh.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaqttii.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pitjuxfo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbxhnxa.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpxdyyw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2loprmixm.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmuewlm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhzpxdg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwrvurn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaimkhow.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fygyxoqo.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiuazvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnnflvq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdciaqf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjdtben.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaongyl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2uaamnmbq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxganfaj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyesauo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2uvggrjtv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpoldmi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvuniea.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2giurwnxr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfevgmzx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzooojko.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmsmilx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmpdmgb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcuagcr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2oefsfteh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrthmem.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2feegihfp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2duppvagt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmuuwnx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkkylem.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuczthx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnjpaoy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppevuf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2djutspoi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2omiluyhw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ndweypze.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxepmhw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bytqopyr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfkkwyi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2alxwmwlv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ailxvkcm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqurnrd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjijmqyk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqahvnld.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oltzsxjq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2msnfruxi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zztxgvdq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2itouksfd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2edpgzeth.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nggskjny.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbripkr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmadrbt.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzoncbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zomjsldm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xzprgghz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shwbvmva.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnnxuzc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vpajcmtv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhubwyqw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdusvqz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2answvujd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2drfecthr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oevibzop.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2iwafyzrz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgmvkdo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfamaqb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2oynsemwe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txquqinl.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeibydml.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzuikgi.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2igoxakaw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oecvmvza.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpyhcec.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlirmcr.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dagvffaq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpycnquw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnssomtv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulocwmun.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aelyeqth.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvsrdub.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pazfdxle.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2edvsclce.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoftpws.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbysmot.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uewpplqz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2etrrqcit.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tizetzcf.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjddvpj.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbppfmlg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiallid.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xczgdmlj.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdeaypw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cibycqck.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgdhtmj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2twsfuqng.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrjgcdb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2audxpdee.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfmvwah.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fznrjqkn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvveknmj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgajcowv.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yssgigmg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smyxwktw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnuilcl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cseixfbt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtwxbha.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjqdwdv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmrcdka.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oujpmxfh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2abyinlrk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wslfvvaj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxdoloh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpvoepe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiqtrpc.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpartwc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmddagzx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijoqhrv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2lmekpusq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnexcd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lconnxma.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnywkcd.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtmhmai.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzkroyb.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhngsex.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eubakysx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2itwffwyl.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkxpqqe.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2imvdcglx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2aeglfocg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ontbbzbu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnohxvoa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwnzdfi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdzqyux.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnzbvmu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwtcccq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgmavtj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyjiujc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgwddyx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqycvlyp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkgeein.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zckrephv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdateqea.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqynqgzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjntalsa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwgbzwv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwqhmoq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilxcgp.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfplucd.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2edvuahgp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzyshob.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xminqoce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoycqozq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjviqli.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dqayndwk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2lolrhdiw.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2donrjtcy.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrqimzd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydggyooy.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrxckft.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2malcnafq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2udzgvqrm.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuttlyb.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfsndpa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2yinvembc.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuxsnzx.html


<!-- 参考信息 -->