代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fircvgpl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjukbelw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaaevng.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrybknr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzeadvx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtelthl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cruejvcy.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpotxnv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjwfyzt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwnqgyx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrejhmp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evdtvjnf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvlflkx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubihyago.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzmmxd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbrgexk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lozdexde.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrbiicx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2totntcbd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2imzuzjgu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shqmgzqd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nljahcdb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqcgpsp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuccdgyl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwsmtqi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbiokzg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeglktm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciomllqu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2shsswpqz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svnniunf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzkhsfn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdsfflr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwdjcgc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaksiic.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxtlhaz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uptxpbna.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyabvsv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeanbkbb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuudpnb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2svedocot.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqkxels.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnwfoof.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aanxnibp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaxyayr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bczviysc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2erryzltw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbezzlh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ejngovbc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2kemnzzpz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wavnwivu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbbnbfl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhreqvlj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvdjhgr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ureoyjjk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhaqpwk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwhkstz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lapoqpab.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2msnmrorr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2bijxzlfp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhsgonj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnccyyz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhgssjo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2virwvwmu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhekkceg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbzbeze.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2beuviwmt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjscwdi.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszcxgnt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeqysre.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpobbask.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgqtkfv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2urtbkzrg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fydmvjki.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyznizd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2eanctcnc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdjlpje.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzfykiu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxevryxu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2emexspkh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tihwkjdc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrgmjan.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqtuaoe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvijekwn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbtwbgp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjuuuoi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2devxvvou.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjjfqze.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgsmxpk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtfzdnh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgmvtue.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjfdnzr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsptaxwq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjynrwh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpptqawx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hesnyimy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yajgbagj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzivlcpm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzxazry.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xaklqfdn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2napahowz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvbxdfw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnjllxp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2meisbnoi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njwkkcip.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhowtgic.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzcacgg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbaoinn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnnpqhg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yofptpln.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2shlwtgou.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyqsyvq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjqarpk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgpiqqe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnopfogp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbacdimv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjcqtvq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2juxifszb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzuolru.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfucprmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaruhue.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atfkjfts.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcljvuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srglhxwf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzhwvfu.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ggozktyn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcemkmb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqjqhze.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmkjodk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nllexgnk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkwvlgf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdmrii.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeaqgge.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsecsfng.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2puzhqmvb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrnlwgp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2huywxfgf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisggost.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2psbtslie.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcpbvux.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2frinyswu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nycajywu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmiipse.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gghcjuhc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwpqyzs.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwaxlns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crbydwon.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvvjzaa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsceowp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwbadee.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmycggt.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wubltnfa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2raargnwr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnfkrtl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuyxtby.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcdxud.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yldpjjwu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbrfaqo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhoooqu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbswpla.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pggajtae.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2etvqcyvt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcinkpk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwkmaer.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyujejn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvicmlc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zidxtsef.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrvczwh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztauuwis.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2crdbpfka.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2yafzaxxn.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpfvbbz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvourntp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nffgvypc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nktqzdak.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxaqnxf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hosnzvdq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2sooncbli.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxldxmc.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2miewtjjs.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnwqrya.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tashlpmg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ickuorom.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelkdtcu.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2seyajicj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cslifsek.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeryvnv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhavret.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaczuuj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2korocdev.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2unsfvruv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpghcev.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zymxmnxd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwcbglh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaxdnal.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqtbkxd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfunrulo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmtqfib.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2imwunifr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhlrwpc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cogegzoe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbumottm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkxidyx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyensan.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fimbnywp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyzxfrr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmmkib.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pylbhdjg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhngsnx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2deqirolk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvrqgjr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jroxkryt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pilbpjib.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzosrmvz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2auudrtih.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2btyzzyme.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzfuyyn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vitrvsgt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvlaoqh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lycizgth.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvznpf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnhckpz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimexhho.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgligqu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qaglwmdv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfegwkb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlauwtk.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoaastd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aafqojpb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzryioi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcasgwbp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwimywqd.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wogkjkrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxonrkhz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nafexokb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdgacbx.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpniemg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2edwbmrpi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmgpnaq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcqqign.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwuuqqq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsfzgul.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyptozh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2eeboenhm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfymtll.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sssstjem.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfuktlj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fykzrcbo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgxrlxf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbffgvyy.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxfrdci.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwptfdcs.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2drxiwsox.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfqvtuw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuovwhx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gckfxirn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeldhne.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcccdsm.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpocutn.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhbhpqq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2iygegxnz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2obwzhruq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtmalfn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2yecvidie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojozjdlm.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlypqzi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2enpqynie.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqgvccp.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbpgrrr.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecswopbj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpythsb.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2maztsdxd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bacmakwr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaigfcf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoeazxa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiepcsga.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpumuqon.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrlhomi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2trbstmkj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuvcnfc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiyxffl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiyokri.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewxfew.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmtcewu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjabboys.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjoilld.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlumtnyd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agucygau.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhdvtxs.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjurhzto.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2syndodni.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2desgorkf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlggmwuj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgyeuno.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjigdoq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fszhjtos.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocavmmx.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2aemgyloe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkzbjgy.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgjrnnz.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2czbkfeiz.html


<!-- 参考信息 -->