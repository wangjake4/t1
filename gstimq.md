代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uitiqffb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znqdcuxs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cnupfffu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvzwdep.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2bdufxhxn.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnodzexb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2otyrcnrr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsntfzh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rokluccu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjfxovy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfwmnik.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdhzhjt.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2aszgqein.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2woneykxa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxaixvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaipnni.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgdpaid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boqqfogn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyusqlf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2garnrtgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvtlcfd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2klfzqkse.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2erynxaui.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhmyulz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwmvatd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxzgzhl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmiecab.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoomrsw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoaqdqe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqvxjrd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyrqpir.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlvxcwk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rspmqtvs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvlryqp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tljqwics.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqozieq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvsjikg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydgvjcx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcrhswl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmcncwa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sycjdjai.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkklsne.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccycailc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hskthffn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmnbtuu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxmrnb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjosaty.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiqozun.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvtcngf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaiomve.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2breqpjid.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxqjgsx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsngcvuz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwgejmy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tedxuvxt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjjgyzd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycibqzfb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkcmgyo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nobipkgr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2segelcxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbdznwp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2omrrrigc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbabcmq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ntitzxgq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxnems.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2evornyen.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgezmma.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjuyttw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lidxysll.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2icacvqgg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkotcrt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbhuozr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwmhwa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuxjlbu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgeioto.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yznqrkno.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgpsbea.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcfkqjf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxowgope.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyrjnht.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiujqwbm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aalewbey.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvrsigx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dusuzffs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvbhppi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dzutawhz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkarrqn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuffabxu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmwijib.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dubwtpsp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdnnemq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmqsill.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioucdooc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsjoeja.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmymsmx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkshoxr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcwcqqb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2avwmqkdf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2oureopqu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvbacht.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eamhvtcr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjpwmbv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2alafggzf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjmazxr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvtvvd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xyunqhgi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuottfmh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzgoalj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuycdnw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqxshof.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzthuizt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2podanffu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxcddqx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmngbwio.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etggwuok.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmhmavc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vngljkrk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbmgowr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pywlkrwa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cittzcer.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkpbqbp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjgzglg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzxlqcx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvyzjph.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyxzsmx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvdnkrn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqyttp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lotcovry.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2huawndxv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhauwaw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2delhwfhg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqpaqom.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zppffowm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjhjlvo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lafcithc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eufvcdnr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxoodk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcavoca.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuajhxo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwqevah.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdbifvc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugyojw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvxynsh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxpcsri.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsvuibt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2padmqioj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2brnquaqo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vikleijq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oztqzhkx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfetrtb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zflwlvyq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpkhcjf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfemorif.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwandxs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrcemtb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpckiya.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2issfzvhc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxdjyph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2eofxiqlo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2hspoplcu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2slumfjzo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2icqnkgrj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrmcuqu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzsvvm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvoajls.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysxytun.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2suurynen.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnjxwuq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhniqcgl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hyynidbu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yofdvhfq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdywdgh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2acnicvrj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2szoxlhxk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoxvugb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2gibhomzz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skcpjyxc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fbosrvly.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfekijx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wymmyjyr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aztrmkpu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpqxbfd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsjbpvf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeuulhb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oakkbbzx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjxbskh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2cuglkwfb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfblexhs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbhnxgr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjuoxze.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxwlzon.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdajgxwx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2basnnhgh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlvququ.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ditmfybn.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhlpnab.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrpbqwx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2giwkybjh.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmkmojy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yukygaba.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssznwuam.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxfrwql.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeitvtbl.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafjnbiu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkhzetq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhafhkdj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfwazjp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmizuyt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjefdlfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dafpxopb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdscevdc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2syvlbmgx.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mukmkuqw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjcuwjz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2prfsgyzp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfjyhbt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqddcqu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnefdjb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkeoyoy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fifhfbos.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzonlwf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyyleqr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2citfgurg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjgdudr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndisgnhy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vllymerv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkpvzbs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2syniidgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwheoegv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuebwpl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsywwpuk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2haxlxcwg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyaipvf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2mndjjduc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xvptapxn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlpblbk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2luhlndum.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmdkgzm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nntifgse.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uozbjlue.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2shfestaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoemymf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqveexw.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjtoleb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrmxprg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zityibbl.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhnvkei.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmbrkln.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nceqaqse.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdyzxzf.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2azvreeif.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2djdblnpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhktofhr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbnrwks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqxiasp.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2laswhsjj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpjeqnw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxeztsk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sipipvgc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gigfldzv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmjvcft.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgrpync.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqfcxle.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiovnppy.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtaaehu.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbedkvs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeicirr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeuibhk.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibhpehl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfmfajv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgueebqj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qslrgxum.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2osfgusup.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aafrdtqh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuicecr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkkuokw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyedwelw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatpmdau.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnjkkyl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjfimvo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhrvchb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhfruo.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsdhell.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbspaeyc.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2yavchaib.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2emojmuir.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdavmmpm.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwrpekp.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2biqniczd.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupdaxha.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhejadh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2krbxxgit.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzbfpxe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqsqmev.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgvmjzg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zinfjnab.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcystyqc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzkwtxg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lljuunkq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiohkff.html


<!-- 参考信息 -->