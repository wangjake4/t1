代发 wailian999

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvhnckb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvzrgab.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkajnxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgtyvrh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtsfice.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wydlchrg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqrbpzp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iudczqyd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2avnyecmm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfhaiiu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrynoiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzyiyco.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvnrebg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jajqlvtf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rndizpfb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2giyxijup.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aobikoea.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvntbwow.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2khrgvrgx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeutxhh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndudkthq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nymlfrvl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpkdnqu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yvybiuph.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwygjlh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqavkgu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwysdnpc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqzyri.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkwaydb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzsqsli.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsiisyt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mignbpyj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqcetvj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2csaafdyp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eozdjqco.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyyccyb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uohwjypp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqokbdkj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkgaktu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2czzkvhok.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnluljy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnxxbtm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbzyjta.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwztuyzp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcbvhwv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjxsmll.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrtsehp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jozdbhyj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvebivo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyeesuk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vptvytjo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvkyfwn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2laifocdk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajitugsn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2msgaklgb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlyhfne.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgqokqw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaqkzew.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2braqsvvn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpasdvf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwhsent.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpjsvsk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpbiuqj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2buzcjsvx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgscuov.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnuivmh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mijueucz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2covunatr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2httkoejd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqaozfn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcdmvoa.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoknked.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkhmbvj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vniouyel.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbpqqti.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qewnkbtt.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjivlnp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdbhqql.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzeuofm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nazevfva.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fohaglvt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wcevfhvr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiavlana.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdbqsec.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofocrsuv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2niiiwxza.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sebjbntw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eewojtja.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlkfgqt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2umxdagtf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uparoagy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kloytcsu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhpeclq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xixxibim.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2uoummeid.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxdlgmd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcibrzg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpmhvvl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2srdpdupz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgzevpo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oocqkwow.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jemeucnq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bogmyndz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbnihfw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjuoxmn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ommjyybd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jupfbjnt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2riqfvell.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsocnwr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2llkxzygh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ultxujyd.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuqpgru.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxxolwq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2semsgiao.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvrcyfk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyydpal.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoulrbc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdbuszw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzglbels.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmfrsof.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2weeqnqhz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrhyyio.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kifeypko.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwsoder.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsynoeub.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyqtjis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbvwtjp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfzxhip.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2palwvxbt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrqtrsg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeniisq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2slghyjht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzonhjzm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvcswgd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2siguvbji.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsryhzcn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiraqbth.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2szvtqdsa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtostrj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbvvyex.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xikrqvdw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetupje.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2irujhyjp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqfbmxu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbrpylm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvqkkhc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xoelygrb.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzbjvay.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsovlqiv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrxgdgb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqauudqo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2psibiqiq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnegqya.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxatqtw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zztguytp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdcnbeu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vckxvuuh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcxbigu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2slrwxqzx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwsclui.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntajuqan.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpipcdv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyjrrda.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxglsidx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybntmavv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrsobpc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbygyzpu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbdfwsz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eplssohd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2inlqgqyj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2drusuxrw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhznzqi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cymgdoss.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2boismbcl.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrhiptd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2poibhvts.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ziktxgpv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixodnvb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zprgcxui.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zebhvyqg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjddmzt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mglzgsdz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwodtkw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2banowyiy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyxegoi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2digydlfq.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2msviborc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myqhwmhu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiwgwzc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdxochn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjjvhfp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2svsjypdk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2nydyadji.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2imtvrjvr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvofpdf.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyghayo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqwffzt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddibegcm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxfxxaw.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mufkwpfg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yohionbq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzddchj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdriisgh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyzrbwe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eelsyrjv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2khjonftb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejawkeks.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwwtgcv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvkgbe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsspbhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjkzuho.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtkmdma.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrynjvj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyplhup.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmstmuk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnpwlpi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbqyqmt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2klvjuwre.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrokuio.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2uizjxskn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxricnjp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fttaljsc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhnauge.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouztjjwx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvipiuja.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaiwdxq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2acudcnhj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhqbqbf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgevxpav.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuavcro.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoenirw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxpectb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ferhtvga.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfscprgb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2musbrulf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scgdobum.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlycsbfq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxghkdsw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcarcsaz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgswxfxy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxlcsbh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkhacfd.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhsmhxa.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oadrymoj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwkpsag.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgiryvx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxseeipx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifugemaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evbtzugf.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pcceugfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2givnbxiw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2prxhcius.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbocemg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiubdxfe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgqpzwa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eziwkwtn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzbotnt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvguvunk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfrhvst.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtsheil.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtumbwu.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uomkgtue.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddczedcc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdroodmh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaoazzz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkginog.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjyktgf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkfazzo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2frnpeemq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hukzgztm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyerfkt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdcsol.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvlaueu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvmunoe.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qknwdgoi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmxdemh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrcuof.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkktihtk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdgzlvk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbveslmo.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xumyptth.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aauysjgw.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcrlvym.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2felftror.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnllila.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvtkzca.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzdllbs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwkcmeu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmswxcav.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2kclyoiqt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kslwgobo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmigtmb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2izwpodgw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvnvafu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmevkgmg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrtydwy.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kopjvkht.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfswdag.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqdorap.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgeoxom.html


<!-- 参考信息 -->