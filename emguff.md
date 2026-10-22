代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wdldpstw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsednzqu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nguzufkp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnohzkb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2alzqhsye.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfsbwni.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sswvuzeq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgvbpea.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrijxdl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbkigrs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czhzzbsp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fudyiedj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjvpbvo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afprwzfr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwvetch.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cevnazye.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcmofwb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkwodpe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnawezfx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmgwtvx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxjbyfa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2glegjaok.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmfgshe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjddgww.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2razyouqx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxabyruy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdocesi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2axfcievf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiujgel.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnspsdea.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2avfjmeam.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjavprwo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyojbvm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pscszyhv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvfolps.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cttwvlwl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zclgvmtz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkxdruj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwlorrr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sspyqmkf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pphccnxq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqamfwvx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugifhipq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixstqzaf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdnubix.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmkihyt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwtliws.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aycqfzla.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pofdosii.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkretbh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2aicxfawk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ambjfyla.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpgechv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gitipowe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbtikcr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpmetnf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcbxslz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2amkcuqun.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpvshci.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tstnviei.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrcbaeu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvwsthc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tciorusj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2teasytco.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgvbbzj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nolkrfna.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2edvpmnvg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cncpyyjd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqzejfx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dardjfxa.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtixnx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvebwcy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsoskkx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kslwqthv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qamjqzof.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2udrbmsrs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvdojqq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcaoswo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2etbhtits.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpmrjib.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyjvsqc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2kouemxrt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jovokeep.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ailcgehx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdodivw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2baahwfbs.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqxniuv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hddutfgz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2derqyovu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmgtexy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2iudqxilc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfwtsvw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbgeviw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjepyxxx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxlwtrw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2veoklccd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwngfsdh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxcqiol.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzcyabt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgpoboo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkekryms.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfilfcx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbamujb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmnnffb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vhklhroj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inffvlux.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2udwksihq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrnpzmy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjpiopd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtygbxl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sscbxuwn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwkmxqy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuvdhkg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxjtlhb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxihjxx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovocoxba.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2okzksemb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfkbqw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjhcsax.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2doljzoyl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qafsdrhb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2utqibjzh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkehpcm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qxctzois.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdncxhn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwozynwh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcrhckc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eumeloof.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2odobfycc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jumkawuv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsinjuek.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2oiibjiea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwfbojg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2exmyoerg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2opucekbn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnlhgml.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vldnioda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwnfbdg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jivrzyhb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsjajvp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrbfwjd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2oonnmtdk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkenyecs.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpvdmgj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2txrmnnjq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsxgmfg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrxjfcy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fifjisha.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnumafsq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tdixaina.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwbqswy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrqnbre.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgbwpvt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvnbjou.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyzfkrv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qaszaffr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oecrdydw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jovpxmad.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nujlxeyq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwtsmtc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2muncrczf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2yduvfrta.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsisbgjx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcfpwij.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vgytfoip.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlxvzbq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmslxaf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnnrmqx.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ouehvdfn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsruleg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qheoeyjp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2egjqfivp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2shncfmqq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqvcuzs.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyznzruc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmdlxyp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbthhlht.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2puwgvypp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzicdtc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2noizerjo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoejccal.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmeynth.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akpfdgiz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbmquoi.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hidkotce.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuurgna.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2okhdzzwd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsorphde.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdpwifi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cneywlcv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2npegripu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpepqxsj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhlrcyy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucwjcdv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvensboj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rwafjofg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxtzjgj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2isrimpsg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwapwmoj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdjspre.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afpiuqtb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azsrmswp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2trmthhxg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhtdxmo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyspqnbp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhmohll.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2auqzzutk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyweserp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoteyma.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lchfiarq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbahyipe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxucmjyq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2btuyzcif.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcnkvsf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qndnmshi.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwadguo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbdcufg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwxzbav.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvwjmbo.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2larfaqpc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlntxtny.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqanidx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rigfroua.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2koqbdkph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfneixj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhasmvht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhydbrg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryswpjst.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdilfck.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqedbwz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuoddav.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvcaqcx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwpvuse.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfljezw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2uefnwhpk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoxeukv.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dikavnpv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lcodumum.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2plrfldpr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuelrjj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqtidsf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsczvanc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblwulji.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mggqksbr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfujlqw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2geszwljw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkneklq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuujgwo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wteifrbj.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2idxqjgog.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybodada.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbiwrof.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2otykdkuo.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqochrlu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzjkqyi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfurgpw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2imbdpnxt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsoouxu.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzttidfm.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwirbqhx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuoucjc.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwvnkli.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaqqmgl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2guhdmxwu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeuuupc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2buldhxna.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnxutuh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2evhjkflq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftojrden.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjotkpis.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbgdfdo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyltyuxk.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrwpter.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmamfq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vulezoix.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eedbjtvh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfyoceh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqctildl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbkhfdb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytphokkt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhydvzjf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjmnfca.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qtafdfym.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxbhbyp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqbrqum.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uohulfki.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hemkreev.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqklxxah.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoyvpke.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnozvqo.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2veaxetok.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zprbclxv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2klvrvrdo.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfysdfk.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdunonyv.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hatiphot.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jicnfaap.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjrzbrc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjexhad.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqvoomj.html


<!-- 参考信息 -->