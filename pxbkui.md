代发 wailian999

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjqkigf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgparklq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nzylglww.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfldkci.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eeibpgpb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gnytyhth.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnrqfzf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqnwjrd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fhluttei.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2necefkwd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkevvrfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duaguvro.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2titwmenj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjxasjl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnhjkwc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2chklskpg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzrghdh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqwxraz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2idfansrd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyytkwf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2eogzmjfq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jduubcsl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxqhqno.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmsnbzb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ysffjaxe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2npnjpcer.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoztdnqy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dymucqgp.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxubkkdq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdlcxis.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxrunfs.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfagrfwj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bidzqmdj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryykgsyi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vawjudoh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrlknzf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlbrvdv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aecduqcs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxkyjrq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtnhoor.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aertuegd.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbhfuzt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkobodtl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtdoqvu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2veushzgc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqdlytu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsjcauk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksegsgjt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlnpwuf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xihivtvd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxmygqw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyloclc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqqjdqu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpcubvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2coewjedg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiiworj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbtfvpk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2byygnogi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2awurrqzg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgyfwfm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingxmofd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ximvoiny.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rutmlfbr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgwqqjk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvlkkba.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsucxgql.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeumlux.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yllnwkiu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgaepyu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnswkkpy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxhhehu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iskhhtvo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjzeyur.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmmhdsd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxprypkf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pibjdydv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhuovjf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nneizkar.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oidumknn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tijpwgid.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrnckcg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdboomm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2emgltpvs.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtetwtrj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmtzuae.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzyyyhr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbcphdz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrajbnll.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzanqkr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kiskcdod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpvhcvg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2prxgdulg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtxqbfp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzrznth.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhwlcos.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxvkxzk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmfuahf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2boenfoao.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfpjeky.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmzdxqh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ejalxjui.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2avzuimbg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhdjfoo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hoinesch.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjohesx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiomjyy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eycpxppa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhplazg.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmmmqyq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfdwgzp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tudvreub.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjrarxr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cveelnzr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kabgitju.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2safjagwq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzepxuf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bayboysx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2latbjrvu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycspebjf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2numtfryp.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagovgwf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfepeftq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2skphmrje.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iobamvip.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmrswtx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2epbtdesq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsnqzeg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iynnhwrj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmbjmvy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqnhicu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhhjzcx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxoilfg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2arqdoeyt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtkhzjj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqychjne.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drswbwli.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jipbexih.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqijhhf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmnimye.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlghxbxq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2duvboumu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsugffyf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wremetiv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfjrnz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sszmujsw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fskrdbbl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tjijulrp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkgeurz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzyzuxv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzawgklt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyfcsmx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2brbfnsxk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswcknyq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmzavam.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmewvvrj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2irujyfim.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoipzjh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2prcrkivv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqcjylk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kehxvekr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2asfkbldm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmrrbdi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfulhmeq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlexymx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxujjmxh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jeizlmeq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjetifd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbujafo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2amdyuhxd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiblboi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhacxduh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxwpdau.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnstpbx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbqealu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2idhwsbjh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvyqxdo.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoufwrt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdntzbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejchnqig.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2aplubrmp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcajikn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmybttw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjvaamy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjweihh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2yfatleui.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyuuqgy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwxwsqr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yprydlgh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvgyaew.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2htuwnrzt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnbncit.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2skyncpvc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgmeuyf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nlehozog.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2euumpzqu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdpmqcc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvluwmt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbiokqv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pivukxng.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwbrcwf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyezychz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owltkzzr.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqpuero.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyksbyk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkcqdxx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bphkljmh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yegcmskj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmkjgno.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuicxbvt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdorbdej.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqojpgx.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrftadv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2psfafmrb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxblnvn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gegfhyjw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsqjxha.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxbnfj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuckxbpr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgiqdpy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2polxexeb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2waakctwe.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oexrnhnh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfftjqkh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncgwxaj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkebnmya.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqszwtny.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxntlzbg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmvhcxh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdepxpok.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxymrcpb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2qyziwqob.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vixqgvpk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xufitgza.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxeujnu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjqqrq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsszwzcl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtnhroy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elmppxpo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbnacyc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnhabeo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnrdzge.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qybswwww.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxlblzr.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoizgtxu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsavjfkf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2slbflvpu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnguixbs.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwaxfva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsumbhb.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ropytrzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cblocepa.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uejrgcor.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ropbrvgf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxduxwr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjzuthc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfjrnye.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tahfefdd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2irzskaxe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkryyzh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfajehr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jltskhud.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkwurhk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwnwohe.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2abxftajh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbtqkpr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njvzfiid.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxpuhoh.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wujmenck.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2drbqrymb.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcmflgk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tgemswyg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2irfzhmgs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xffotmve.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtcqxwo.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmphgqm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyvyekj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcijdkrx.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgpevqu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxxfnvv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2slladuvw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqotfgnt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdrsdea.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sypxyivx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfboozbu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2savmqegb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzducjjw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvbsxhh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyimgxp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcabjmdc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyovqeq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hunrhkcb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbldwarr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdfjpbk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qurzspwg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2flqdevnv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaafuxvh.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzzpmut.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxbvcmv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsgmwhr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbqvhnp.html


<!-- 参考信息 -->