代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2utsopdds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwaxanv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2knvbvpzx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zogrjujl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzqcyj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxairrdl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffotrpci.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxrzolh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeridew.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuruokqx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlacdin.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sebyymaq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2idpkshfg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgyhsvu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtcwmbd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfagczp.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npnitsvi.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpshhae.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kssransj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzgcsie.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2srsxtimx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqnesqk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdelwaf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdhcnxf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2agddqtwj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzeloof.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtxggqg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdgcomv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dljexawh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wjffzrta.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyzgerp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2prvkjatg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlvvoht.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqnrvvk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfuhpbs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xldxypgf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodlcgjt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwxfniw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfeagyz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2szaiczoy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxclpoc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jebgngcj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2stmtbvhx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeunlmuz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ueopiixb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqhiukf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwjdlyu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nedcuvel.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2spszdbcz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmarmmra.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeakgie.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuooshx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipecedvc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzjyhsm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xknymirm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtsctii.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2txoeszrn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2axansqys.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uptexnjh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgprfhm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbgegko.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbftjenh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjrxlrb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2loqiocek.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipciqyjp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxmmhko.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odrwasyb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuwlpfu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2chbxipgp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2suhqqltp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvmreos.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxogueyr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdzxkig.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsenuhe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkadhvc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgusfp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbndukp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnicomx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2aesvpgyf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrtujrk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgajblbj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fkynomyw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cenuelbi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2drrjizqz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xncecqqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2knthvqyw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2honpwwwy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzlyugo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxygzxe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gptwxjsn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwklsjg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwvhagm.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qlozvarg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbagrxbd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bakdwnxk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxiowrz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2niompkyq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwbsvaq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvcgyvy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuxligc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcvijpg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuymlne.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2atwiirdm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaeszrf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdihywug.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuukcmo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqktdnu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfddqvn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2conmblww.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhddtnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfncvma.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnksayl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzkofq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqhpjwk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztumgdeu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cavskvkc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmxnaui.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlilnhap.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjjwnnl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycglorot.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxbwlsa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjtxipl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwpwvoy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uycwarcs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gchiecyy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kqupjyhz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2joekfref.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmuyhuf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oofnxgvd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrsitjp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtcszwp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmebtkq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2faarfnez.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnedjgcb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2awtqdvut.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2frcvwfyf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnhewxw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdextgfo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drlyyeau.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qimzpthv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcjqjkv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkepdzgj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2thjsrfso.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxhrnvy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmujgzl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2idfxzyup.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkpyxaf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qahnfosu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjofllnn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oquorvgm.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhojvch.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjkkbvz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tajvlglk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2abgexgtc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgohchsa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mlatmfhq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqsnbzl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzalxlwj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2oppssfsa.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uncuwxzr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2benxbwkk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxqvvws.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2chlnepbk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqthwmnj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkyftmu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atdpisdg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2abiprgwz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jovxdthe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2squceqet.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvwtuja.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2owpqbvrc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oskmlfmr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwaorng.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmargcs.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfxvogx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bifoofvk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqdswcw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmceboi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkbqrqu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pywviocd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqzdbdt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ygflvsbv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utcwllqk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqrfezj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfbjfpy.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtayxxbn.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqzdhie.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2menzgplg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamqtvrw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abgnufba.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkllyyx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2knnbvvuz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnhuzdh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrnfrva.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwakoek.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhguqhpb.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrniufr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jghmvfnh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2azjxtyek.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfdbfkl.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bczviuij.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pppdrfzv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gghzuucr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2chuvirxz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2imbrmcyj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2btccvwpl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2irdhbnbn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkfnlwc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqqomjv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tpncbfjr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqctpng.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoukrqyc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gohprics.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhijlyr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2frcpcmgk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fabrkabg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvbqpqb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwuqbgj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdfrnbt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhgzomh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2snzshfns.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqsbnko.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oizwksjf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekobkgk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlupcrly.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzibylwl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idmcodqa.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eonarhxd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeyqouf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2grrhylwb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwniisnb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvloxybr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndycgry.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nalxozub.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfvycmy.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmysbnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvjrps.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpmjrlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jivzgztw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuoggvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pcelpbpv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkwpzwu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eipyluhm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdithri.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2llszsguq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjuxiyv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fokrmcqp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvptann.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpvahdt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2iaumgnnt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qphefxqo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfixqorh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbwidqd.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcnoxbq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqyzydo.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxxjecx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcljlkrd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcshelz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmmsmmz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhftsofg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyavhrgu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfeeamr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbmnyeu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlunrev.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxaphad.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2etevakso.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wohzmhac.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wghxkupf.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ackrmfik.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqnqsia.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnnaxwe.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dldmlyqz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2grwvbxgf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tokovvzu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zalwdcux.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnywouc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yymawgrz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2rugxxzwx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkouiehh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bezpqixx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2khmpkuev.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2txflghlh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlqfooq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzouoox.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolmigs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqifqxl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyllgwyx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2afockxny.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkcyeua.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuanwkvt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mubvzafi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hixhjzpo.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvdenjm.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gntqvrft.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2srbnmmox.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2omttptat.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jufbbwks.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2arawbphx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2spjvzjxj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzaeqai.html


<!-- 参考信息 -->