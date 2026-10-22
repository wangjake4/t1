代发 wailian999

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfsteeq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdkgyzn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqfnqst.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zawhqdtg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrurmfx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwbqboe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whrbrbpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndthzawf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsrejni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azrnurlv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2grtslyys.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtgvvxq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yywxdrqq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2otekwlqm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcyxcuq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkdzdbh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwcouvt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnukhzz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgltehfi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vntsvywr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2iypspiwv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqrveud.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lemjerpn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbibowdx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vealxhfx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kghildpl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiagsml.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrkbpzl.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqktzuu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnajtwq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzuwsha.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqshkvv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpbyfhl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyjzfyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvroyfr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgczexzw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjrwhou.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmmvqrw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfyoetp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsulotv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwruqbvl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpiehka.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uasaiwew.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnpnhtq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhyeruj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvpggdx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfkedlz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjoqdeu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdglebs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghwfgfu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkqjehf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytodlbys.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzyqoal.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjoyshl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnersuo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sduegnfb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtohqce.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2obdcqbky.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlklloux.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmlwqix.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wukcizyg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvyuqfa.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfsvecj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nklngxwk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xruapfcz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzguog.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqkrcvf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wursyxby.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xayikvbj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdrbofr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzwexkm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kweopshi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cthrwmiu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2almpscxk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpnpwpw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcbkfga.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vylrytru.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2idawoaou.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoyrnyo.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fomrxtny.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdybjuo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqogmvlm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnetugxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhxxvtz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zampiqfj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2opicwtwd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyzsxky.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2exjtprzo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrmnqzs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxuizm.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrmgtqm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2koqjuvlg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddubluom.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscepmao.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbpxfyv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmowmllt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlthsrr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2okfqjpzp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwyizmh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bmioaana.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rivwnead.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjiutut.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqihpsd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhpgyvw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzcpmcp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvorljpp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkhppfx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jptdphcl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwaeyj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvqivnm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2remkpcro.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kndejzch.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnymnflm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmgatad.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvzijop.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiekzdjy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jznkdtbk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfsplst.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtqoebo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkrpqej.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqecoyyb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrjlvvs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoaatyf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibovceyt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2llarqzks.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcmydqy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgqwztl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqsvmjr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmobjjwf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awpxwlmx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxrkpql.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hypwzqmd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bugboqvh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaowucc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwsoqmq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mntraplf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqiiusr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxbkqoa.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuwcbmk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjtpdmd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrneutr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2djbwywib.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kcblsouu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuvixlk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwkrdhb.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vktqxlfp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvoybut.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqseqny.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlwmuql.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytnilsx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2effskfir.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmrhnae.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzvckat.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsruarov.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cudwhzci.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvsaveb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvtyeap.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bafbecpn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afbammys.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjujyfhq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubkhnxv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jniddbbb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2svdqpqwr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2onprdvsp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jfubaoiy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2phephblt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzjzeom.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqhdajf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2thhglmay.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvntufw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrhsvry.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2icmtasri.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qxykkoab.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldfbokv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddocvfpz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rusqmsth.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhkewvj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2efbyxlyc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2olpjvnnc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkkarpj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bksirvin.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqyykff.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjwmdnd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaqhmsb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mdieesbq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2syoqarea.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2edtexdha.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2szivwoqn.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jiluaoox.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbgfsez.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xztarodd.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2naszdfnw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyexhwp.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejunaddl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2assfmpbd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2psbtmszj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgntmil.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhruykdv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgujcxgq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzppntw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzlonoz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrhkiss.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfgzqir.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnlwhzf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjspzsp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfrjnnc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmdqmar.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrlrpla.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdjpwoe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fowmgafj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzzrmqz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzrsqdo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvunbeyr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdyqvjn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtwjemc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2wexrdfzf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmswoar.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gehdcgas.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcieprj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kralclgi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfiwcui.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzmpqqa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnaxcdw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwkmyfm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvnrbkk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2lplvduaf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkanlcz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsgqxer.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqekjoo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohelzxjv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzbnxyv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qroiorkv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdsbau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtdrxqe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pppkdbeg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhzwamj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2utvhvlaa.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpgedwi.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdaxla.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2giigfins.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwbwqhy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2myldzunl.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxofrf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiefvkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2myfyotvu.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjdqhvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcuhfqn.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctevcngd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2entpdfdv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkrnbdo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2flvvjqsw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmlpvqp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuwzwyo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhwukkw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ahekdpsm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrsloca.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrukdsig.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qgamxyxh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnxdubc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fygoemzh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2byqfkrzr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jexapfqp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyezgyg.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqkhthd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iotyqckq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nywynqiv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yewiqtzx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaimucoj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmzbojg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftzcuzi.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcroykp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlbqcyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfjhtmj.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkftofh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2sedpsptx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fabmcozl.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2mibsiwgv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcllzylm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lebqnwog.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxzjrto.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uerksomt.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifshopoa.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2napffpnt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhsmnje.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuxprzy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2eugbxlds.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoecwxtk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcxujvf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2clrzddvw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2umnmyrpj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzuqweh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmydbhkc.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwhzisq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbceflec.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbumbdqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2regjxwdv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhkrwfy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnobcmz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxujzmp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpkqysi.html


<!-- 参考信息 -->