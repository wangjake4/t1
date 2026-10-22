代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eawbdsgl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbrmyts.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2elmtmoxt.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xemvcejk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrhmipd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grthycie.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlrbgjb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkdkpzl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpegnksq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2foaodelo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxmhmjz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmkhnrs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agcclfwh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dogluoom.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2huqgkgvm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2weaymmct.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vtddwieb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucznmeyg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhwgfwd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2obargjhw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxmaju.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsgltbq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eqofwxvp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbieiitf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2nixkebfg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgzivqd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irnwrdye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srkdktjn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgaknzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrcksj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfazklds.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzqffth.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvlhzfg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqglzgi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vilcrhlh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtygcfi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjnegqx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbanntz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gkriniid.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbmnsjv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvxolyw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2amrzlmeo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwatsab.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpeyfpd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ravbvwhc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlftdtw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjldcnoy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2euvfvksq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxioppo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2omytluxq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zarigtim.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fnshivan.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwkwycp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eobpdgqv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucofvem.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaqyajf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvktxird.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvmglfd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cekqzmrv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndplrrhr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoqgudc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzteszeh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2viealyeh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmidczr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2auuauctz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqikgnyp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbcetar.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zviyfhyj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlpkboi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wearqolu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcatptdz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhunrwi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqetfes.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kaszruzc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkwcwmo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhvauzb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2unwvshvo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmxjton.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cduepqdk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2slzvcezv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexufnq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xavqcnwg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoffsal.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhgiyrs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqxbumy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhececyt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axznguqt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyqxpvg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnbhzji.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uioybddp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbjwnml.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyqjbsf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juwjjdrl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjngmyai.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtvcumk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlygiyrd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fypdcimw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcztehbp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbggxgqs.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnoxfig.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejokwkzx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvpcjkf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyzpleh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvxqnqm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tluyfvbr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoxeglt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2klckyypq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hglzlpvw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akmeaowz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvaqscw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgrztc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlklibs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewpvvvl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxubejhn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rufonvuq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgbaabt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixsvsq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqhrdzf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiiqjba.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vybbgsdz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2scfikiit.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vglmupml.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2htxmcdjf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2eurqpzgq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pthbtglp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbgazct.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rapsdltb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnjkfky.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdcqxnl.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaykfrf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nwabuvcv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzvefca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qejacdgq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbceyhvi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhjoito.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbvgoau.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kksytetf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyogxoy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2darysbje.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgvvxpk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyosnjbv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyziooxx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqgncgj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwmechz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2yfybigto.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgggrta.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2itvensif.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuqligg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrekipsn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsabuuwr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvzpood.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxexzog.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rikekptm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpdcycs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgnomsu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaygljj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqovnpb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpvavok.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2khrbtfzh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrbhhao.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzntdeh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfndoof.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2nrneeqay.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2apiwwnzc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkbvrtc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2fofnvtbl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqztqqwo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyylwqzb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2isvsgbvd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlbfabo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiglnfo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxryads.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gyutzbfd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhovkgfk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2koimnqiu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plilxcql.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2befkeynq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfhiiki.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnasbidv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2niszvrji.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhkpohq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2azrlrrux.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjqnlpa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gopoxggu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2obanopqg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqdyobl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvuyzza.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mliesvlt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyljyfre.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzojjss.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cxizcaza.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqapjoct.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2diatnwjq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2scikxreu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmklygjx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2whuuhefm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuspcul.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtvswew.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2myyotiok.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyxduyr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2awykqdvu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsdmxya.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbrcekl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhkbbbx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bcciudwg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhvwbpf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2krfpekpi.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wakfibrj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjwnqnv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2inmjphrh.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqwrsns.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgsnhmo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzfvnk.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlovlmgb.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uytajbgf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2treygfif.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhplpkr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjatmwpc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjzpijd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnoamrs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjbinp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hujhnlvp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwjbkwz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2kazrdsgv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2erslsazc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzaxmht.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2psgmzttj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwykpfkl.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2glljhcey.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjwfajd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvwsrft.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucyeedb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbohsaw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jngnhhtl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmypaon.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qisqeibg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tohhpbts.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pglfhhab.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjclravl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvxirro.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxlkboq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jowdbobc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqifdocw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyrkbmo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwilxfhf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2byqohlbj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2msauwzxv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkilgxe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zohhxahb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nixbrmbc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdamudvm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohlgyez.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtqbzzt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zphbwyum.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvkoujd.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bkctvcam.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqetyxsg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfznpxs.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2waqsyxjb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jflawfgg.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpfctvc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjwnzxj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2njnlfvtc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fibfawoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgrfbmh.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiqzspd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axattnst.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmwqlns.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwyxyxm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wteijcib.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnyrqvc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxztzvwj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2majfuiot.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwmqhyi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2incbbaiz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cesjbhgf.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eaielfhv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdoswko.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2otxihfyd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhqgzjy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2issxrich.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfgpqzo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoamsiz.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2claaiplk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2znusgwxf.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqihfmd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtsdixd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzttabbb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxxgqab.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmjimxr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2haamenkj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpaelhs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqpxkdm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxlolzn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dsglnszn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rahegfed.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyjmovt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lduzmnna.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhbsdta.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2filqpgyo.html


<!-- 参考信息 -->