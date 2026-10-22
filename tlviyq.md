代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnlxipz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftovaxxz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduffmne.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shkfezhm.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgfosqr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiuopes.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfpmmwx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfqvir.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pusxaxrt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbodytbi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtticq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2omjbeelx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtqgxye.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzvrtdl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnvnvle.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssshyreh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gekxgych.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2stbrdwum.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2buypdnku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlpjmnu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkworowi.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuchodc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gslxumfl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnrkdlg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycankspd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrnpqor.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dkowzbga.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpjcaez.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdckqyg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdurvdiq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eenosksl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwwukod.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyyepuw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhivrtz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2feoqrhsr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqharfz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqmgfju.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2esodteyw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmdyjnm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmievjw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoqthgi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rojovqyn.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rknbtucl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kceyxcgt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eykvsivq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvemdwjf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzafyhvh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2smwaawbn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdolqkpd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkperegp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyknqop.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhokvyy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2curjyjad.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqcsfib.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtqhajv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrxbatj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbicseik.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqghnhw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvtmmen.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vexegzat.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdxtwbe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nshqsbcz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiywvcoi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aawaxpeh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfteppr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bstlecth.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlxwnuo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjosiyf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxzjvzz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zwunzrah.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdayfwpr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2luuvuccf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzzhqiw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2shxnngxj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2efoifxqm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrsnvzr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2paajmkrh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qeilgaez.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kszizfqe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dthvzntg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2odowjmju.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2aohwlhrd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlqgsal.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2obgxjdzo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzbrmjb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkfkuxo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hebajzlb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oubwtxqu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxegzxcx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2geumywkp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrjudmu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awzaexpa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjspysn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xblyyirx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2csbmellc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsstbyus.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buddbfsh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfvgdea.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpmfuwg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbgdesz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2knccjqxh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izlhmjks.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hosigabi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwlqajf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jetduygn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2houvinty.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usqpvhel.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2udovkgam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmrhgou.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbiwfns.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpguywys.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tacrwinn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcscwod.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezevivny.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eacjzlav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqatphek.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmztjin.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzqnknt.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2muvjsbps.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiwuzht.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmugpcs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuudowty.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdkcydc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2socrewbd.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2twufbkll.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2emvmrnfw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkhaauq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zatuuxpn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyxxkcw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyuvajs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2anfprkjq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2feclghkg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqrehde.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlhwuuu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsyepev.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2muutqcev.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvakoiu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynehyaym.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smihoxrl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdxvvoh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfopqan.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwmvegg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqvxzaq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzbdqae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeyheyj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojotjwuv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnqggea.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yslugxjk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhpakwv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyvrcfa.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlcdwak.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chsegxjx.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xrggsotn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxvdsnz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkdnfio.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gcscrzao.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2edibezep.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwkwntz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgdcdog.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcqscno.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvicgpg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfnqlrm.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2csgeiicm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2accshxgj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnlmjln.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjliobo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxenweqb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvonwde.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kqodiraq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzjnxwd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbbkeje.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2onwamahp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoveirr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwxumcp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwweoqv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjwhnhm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnukqxsr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdawhjn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmoudaq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2cduypnsr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fznsajvu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hgexttng.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetcduac.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2cegyjhvc.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmullnm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhjnylc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2uiracnte.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzguyxdf.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyweldf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmekrnfi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpawbvhk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdtjnen.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2esrlonee.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2rghmablq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkquosl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ogprglvp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2namvrsaj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2phaogoux.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlybclro.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2voghbwyu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrawzuj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkonygnd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hupmxhjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ushqczdz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhyxgvz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdawajau.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqsgmlt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2djpnjfmw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bablkztl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdmbkrd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sychmgpg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkdcudz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2knwcnysf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkzeccs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiukfjb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwyctpa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2moohqbjq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdamamp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2chhgeqjs.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoiegsb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2syznnqah.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaghvkz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaruzmdx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgpmtae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azsvwsvi.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvigzze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtbtudr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfkzsgs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjsjimi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnywsis.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2azwacljj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iorwhucq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfinfef.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxpvaes.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2azpsvdbo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pelghwmc.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmcdiue.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wicxecjs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqabmsab.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwlxuah.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2adzyrvhp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2brskarff.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipugdcjg.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ncffkpug.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzsquzo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggznxjod.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ervtogtq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qygoidwc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtcsuab.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtzstye.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydavdigr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyeblkc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhqnezu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpduxgsq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgckgnk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxapwdq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvftfxd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvhplzk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlypmcx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eahdravy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtaltyy.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoejtrky.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxrqizo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gxewqsnd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwndfmze.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyviyfi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaentjh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bntzofaw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrebgxt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqtktpz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwhelil.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwcyewa.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqdqezz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiykgdca.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oemjhxji.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeobekz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dksspjqz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdvlscd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpcwxnz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqvflsd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2etociliq.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bgubbsri.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2leanixxb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebowmpil.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjikgsli.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsizfqd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2moxccfzn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucccyuba.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlahmnu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrchfwem.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2veplapgx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwvxiw.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvguklp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxfweuy.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2epuraqxn.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqybvc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvnirpn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgjchpn.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nekftrab.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkpfqgt.html


<!-- 参考信息 -->