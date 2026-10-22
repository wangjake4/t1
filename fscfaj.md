代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ranesrnv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzkoiiy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdapbkjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwwbkhg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2nlshtyun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsffyasm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxcpsan.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2yprtzdax.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxhqczv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtsqako.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2wuysowhl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtjvewt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsisehx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgnkeoj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeatgbg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ffleyxfh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kcollluh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fojpiqik.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2abxtkxqn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzivkhwh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqnazuy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrangy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvuvapg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoeqlpe.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfrihsr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrxfiaw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkvuiyd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyenxyx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucavnxev.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2prsraxig.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafjvlia.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2djdorsml.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2izfxrpsk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlqssuv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhzmxoa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgowtpvo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyitazp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iioutsar.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdywdty.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsxilol.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhitboe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jstazqhr.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qwavuufo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgrouqx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxejkcf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzcoryw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlkzcel.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoyvhgo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uydhsajs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2htunlbwg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbvimzm.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zznqmaqi.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaltquxi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pohlyjdn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfubgpd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mffoprwy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xukimmvb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmlsdbe.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoxtcxp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2svbnuglh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2khzntprb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfnlajf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhpydwd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqklukoq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uikpxjzs.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2amctbdiv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2znufggzx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gybmqeth.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzhswxn.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cncdzcvx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvlnciz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzraznsl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2szodyxou.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxvjewp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfwhann.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwxoywb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuvaevf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pszbbtcg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdihzrfu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiayufcv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkpfieo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzdxznv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfkxhnx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkcnvpc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoyjizp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoqsrkf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwujwnlh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiuzffd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvstogm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfseauoy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yadiuxhp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhagiww.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwbvkey.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvymopy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2szvotitn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnptmhc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2laaymqqm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2uncfgvbn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyelwxb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2botswmbk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkayxfug.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2grxnuydv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhogpsjs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnlbldy.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2welgivnw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2esuiclwt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2czsqnzal.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzauihy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzhpbxh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflxzygu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpvntyq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsijtyh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpytvphp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jabrhuxc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwijkzy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmvwsjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egdggfqx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiizplur.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqqitex.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkexyl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mchoxaie.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzvlmei.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2egdzgoyj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zepirvfw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2llmbxhyf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ichvqwut.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhbqmgs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqxnvnc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2almqtoyu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2atpvoipn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2whiwutpd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkummmon.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lvilubtm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbqxtip.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjnunat.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrlsiz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzfuity.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfifpsl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaccsix.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiqpzje.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bygqtftw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2veuumwce.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbzrxvj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yponfdlv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeobdgt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjuuuat.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2okgvbxsd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gayavngp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2omuhfcps.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggowjkgm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2naefzdca.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iegpoqch.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhsmlpr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezyswwt.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2csfotxsn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyaqkcm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaszfzh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnoveev.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hemajdrz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cflvhhnr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvwndeo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpmpiyk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlwrdaz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wuulysyr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypatyuml.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wutpketb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfcdjqj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cskstskp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjcgisv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtktysh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsinnnki.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfverfj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrzujuw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrtljre.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2kseegmde.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzirnzs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpfijcl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjuwxbt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxdqqds.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqzkcfj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2udcssuuz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lteoxggk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2unampyld.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmrzask.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2owhowtzg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bveczyca.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2raqqhayo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jsspsamz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpwfzyr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhawqhsf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngrlrxq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pujvmjim.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmyccll.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtobhvtp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtisdqc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2whgfgkwx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gowqlxgw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dpibcsio.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xejmggft.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2olcihmmx.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvqzraz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqwyhif.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2weqsufro.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2larzbops.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpjxtdt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjwqptk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmyovxb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kanbtbdc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvwsehw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyluiumq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlqnnwk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2isvwbxqt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cneqoonl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrextias.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hseawgns.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgexyfc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjgrkgs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fprthxqr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ergubgpl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2htlefdqq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mftiwhtl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkgunwg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdqodfl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxlbjqt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoavnho.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpgfxsi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvycvtav.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfxjkth.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcmfibn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nooiwtan.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyycjzsy.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yogjvyrt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aawjwmhx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxrazgz.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxtyiua.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xankptww.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kndjwmxw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxtrylq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcztztih.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsopdoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujusjmfs.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzwhfhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvilmva.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nybfgnpu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjbsftr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xundhpvz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2giykyjru.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdzmlee.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxlrdjh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzpsojh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2atufjmyc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2evvuubcp.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvehfqri.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdxyycr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2palaqyna.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpndxbf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oturtbgz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyflufc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2faylvftm.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwqlyoy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmyyaku.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2otqmmkdn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtngbzvh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdahlsal.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sttielpl.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2apfatynr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2crppwrdt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ookfxevb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtzuqmr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxxdre.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiuttxm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkknph.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdawmlum.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrdplmd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyktzwk.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgwkqnc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvjrtvn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2smvnjhpk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qonajrkr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbubnqy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfempxc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jewduwwy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbsuzkw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjqcmxo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvykhmyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2apmuhwrl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqonqdx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlugdwdg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpamkzb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isiofesn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvbycmi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnmknwf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2stpktxhn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2skyxlzto.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbfcxai.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bchvgnjl.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2upxxbkdg.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2iejhpodx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgzvdds.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpbhqwt.html


<!-- 参考信息 -->