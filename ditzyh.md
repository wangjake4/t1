代发 wailian999

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxreeyue.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiquymj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtfmmmn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzsiyj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwwskdx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuryeriz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoukejw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zwanvssy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnnskhg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewthrxmo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qstkylkk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmzrscp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyokgdfk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2myvqornc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpafudns.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kughuxho.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvupqkuo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkkupdu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeeufot.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoydskt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdzqmez.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkcnfek.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvqgyac.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaacmsr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kldlvinz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtrkgye.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fibgqspm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oggqugbu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdfbmsx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfzlnbk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncylgxts.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2trvoiswo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiwwcxn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpqtcko.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wukuvjwb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qehldqce.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tutlrloz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdfkzpz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xssfamjn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhakeui.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2unuganva.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xohvqabh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ponnptwd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2butsjync.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcqmvly.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rszritwn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2birfghdc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaxfcrr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lobkyxfw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cldsxgit.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygytrmen.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdfugxf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmddioro.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cstglgdd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rneumndx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2puwzfztc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlntrvfz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yukohhsz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2socdsasy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqngablh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yarvbiwl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2anugnlto.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2afmpwwuq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoweylk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slzqfxrh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ksypzelf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yurwkiwf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzgiopp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqukhtx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvsgiqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqjldf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbgpffa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uevhiiyg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2drdjkxir.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2clauzdma.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xekpwmks.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqaccsw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vclgzmpp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdyqgws.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgneduqf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvdnsoz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnxayic.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkazjlpk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2myqkxxew.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpqonge.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2awmsrkrt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpihkjr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlonnwbs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxjitom.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlecrjiv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbjhasv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igsdljuq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgkyyl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpfmde.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2yldyyzvl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aztbfwpt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmtfhjr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtmqxqa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvuqxyu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvoifss.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2edqqglda.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tffnolnl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuwqmal.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqelnph.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxnunr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkidwfl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdwovk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowwhxqd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtxqtdx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odynlqpm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2avskkjlq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqssbrl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rntmbckr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntubtyvg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtukibvb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2abpdywvg.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wufmkpfs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hebstlug.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2boxmllol.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkmxfno.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2znpbakbt.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecniegfp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvorkwj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjmgfka.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbosckqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkywfrkz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaydejqd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxilfbx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrbypon.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nweoafxm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2priyehgh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2varuqepx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2msthgvvl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpevjpv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvzwuzf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lftwxvmp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcxeznj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmjeqvf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjatdsy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tctwdfoe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2naiofgup.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyigmyn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2opkjfmkv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkjuejt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zunvuylq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvkmsaq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlwzqie.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzygmlx.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kzodsvgz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpsdfeg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jravlnqs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2elrofbil.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwighbu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2swkaiypy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pemjabkc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdomijk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2skfpbjew.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fllqokdu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnioekti.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyopzap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlolgsb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2olqoyqtu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnkdtbh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2guhxythi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vncirvqi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tdonskzv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovodkkni.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fbewxtjc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlssbxo.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwakzje.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsbfqsv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpsqiln.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmchzasr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvygtddx.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkcxjvo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfgpgxk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlnppcy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tybbhbus.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2edoznpwr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxthgyw.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lynywgmk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaayxsd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mblqmxls.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hltnsmmf.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiyyssv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamfycoj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zymbpzxn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjxwcrb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsotlar.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnacrhlu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuvhlqx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2odlcjtgb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwskyyza.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tzehenyk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjmihhw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzudbgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdymnxpp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtyfuza.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbotmoi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yorctewi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuhreyy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqydtlti.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2yegjnilb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2idajmkwt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2usysiklh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyjkywu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqrlutp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwsdnkc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpihdxg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbpaubb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nluzfztz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irnovpwb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzkgzex.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeawjrg.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xosqjkce.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiepkyk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiabbpk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqecwsju.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmqceip.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aewkwpxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gerqcxzp.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2usrzpebo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyslzrd.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkavayu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2mkidjevo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dchdkajv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbejkwl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpugcnvu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bptlftnl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrpguzd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2pbconuyg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wverthnr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gapgqciv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmkbtyc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyoorux.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2blxukdes.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2algfoknr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2itazrxze.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bifjhthe.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kzztouzy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcjhdls.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kokvhuft.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyitkdt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhmixdh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgurghp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2edvimgea.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kphopufo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcjzshn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yebqbtat.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhbqqrg.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2vralaiml.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mprxpcpe.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqlvkby.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjkajtk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyurncc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2suqemeoq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyxcxpr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpeosqs.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxwzqdy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wfprirmg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2izhwhahv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2edysbzpb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cypenrkk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhxzuvz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2grtshkgn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2enebjjai.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpwfccy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvcwhej.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgknfbi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2twcigsci.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwisuezo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwouhhvj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdthpca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2elozajkg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llockrjv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2phqdmpld.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2splbggtn.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vekymvsi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgenmmu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2scgxnjyd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhgniha.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uofenvgv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmotaox.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsklvqk.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2axqhbarf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpdaekl.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgxnxrn.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktclzdwf.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcufmihy.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqthkon.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dornmdvk.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfqyjce.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfogymhn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmhcrbb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbivkww.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrqrhox.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeilywgh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xryjwvxx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdvzyj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcxzsmr.html


<!-- 参考信息 -->