代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaezgis.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvmwoto.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeyopll.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjanvii.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ectcljhb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2leydoiev.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iavdspam.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fynyuyxl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmswkt.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkejxuhn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uognzete.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bviarvsk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxmaqjs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zahdoljk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgbuomo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwfomwc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pffvmfrs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2apxkbbkr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqgdopa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akurkbpg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjmlatr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xevrxwps.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2orwpnfgz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdobbfi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bopiarqd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2votalacg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtqnbsd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpodpsv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtstsjw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zebkngpe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfosvyeg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bazslczt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfgffsr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxzxwzb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqwgund.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnfseii.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpptgeqv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqpmlkb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmafsed.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sylmujfl.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2idlzuqrd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcullpss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfirrk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2oagxqwdb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaqaitd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnbkqog.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkcoykp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uynognho.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvaodxt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfsxhdc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkaewpa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgoyqsm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqugzoo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbaipmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwqijpn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaguxbg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbqmsou.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqcndtz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufadzfvo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sksqauoj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgutxotc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrptlro.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkejbihp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lctfatzb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjkqqvz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2riwkcntz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2heefsvys.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxqrojf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamujigd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzkdyav.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcbptix.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uopgtspw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xupyzodb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpoxjwn.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzmepaw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvscgfl.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmzzvet.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtxaxru.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnpebza.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzycmsk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysblaiae.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2whdwfezd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2myeefmtn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2syencyfr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2obzcrzbt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wlojzmtc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egczcpzn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbredtqz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohunqxiu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdigkfu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxuohqn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqbetmv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsxueol.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjdvssp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgenyfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2raxzsdtq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qezzlecr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xinuztef.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebpjjgc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbdddzw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadxpllf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xsilnwub.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2uryjdciw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2febgfoua.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktomjrcq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqukdtzq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsuqkwa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2duivzqam.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nivthlfw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cqohzbey.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdnmuxq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cshjuxnw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhxecie.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcmjioi.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snzlivii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbidyrsr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmyygde.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkievdj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkynwdt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxbaidh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtsaynh.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpwqbyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2iirbacxh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnyzmjf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zixkgpmg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bilyarle.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmcqpgw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmnnxyn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oilbvwxg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhufoboy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2yegqbzun.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpwvnaf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmtunqb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yldpoyze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gphvuxtn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaobfjh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2kebsqjcr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeltzpr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhguyiev.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxhmiua.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpzockh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbkgxkv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aohrdjtj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzanuxh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoikyyc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bplicgbc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2suzpqykx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbabnoa.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hyculccr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mphkakyq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ircnsgwb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2otimqqmr.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2joxyhixc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrzblse.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmqjled.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qiibnlby.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmheght.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuddhga.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usvvotuu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjmexmk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvctsvfy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbutfmq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvtmfej.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wiifubso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qssgyydd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xngxjcwy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsylcdf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvkxmbh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyemedcg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoeiljq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2egrrpfpv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lymvoeur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeqpntd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gjocehkz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2phdnkyag.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqngjrgb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2euriqwpv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2evlnfjzd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsslwsj.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnamvovr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffradwwv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsaicel.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrvitde.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2isohrhus.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoipwca.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtohkcv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwovbzas.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yybmoftz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2udnxesil.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2uygczgye.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2snslwidm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2krdufyft.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvsykxf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcykmii.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhigyega.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2utsvplpo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqumkme.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhkzamx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyjskjc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mfarrnmh.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2roygizyn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqdbakl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnegcxi.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2khsiaiad.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tegkuqfv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zovmvrrp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtfymys.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhudgegu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zynbnygd.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvtnicm.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyyjndv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2achessxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lttgekzm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cptdjjhv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swjizgrm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2imcaxwkp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxrbplf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhulwczv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jcegjpmg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoxvqlv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2joizsuwj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcnfmfn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcxmfyr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmdokwh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vllznjsx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeavpzk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjemof.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jehqdunk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2naigzlll.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eywayadt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfzwuyl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfqceis.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxwuivy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaibmgsq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgllbgxy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbwahca.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zccpevvx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2nefsluyh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2chzmyzvm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhbksmc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtakvms.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxekjoi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mznssdqn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuzwfxi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtharar.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbupiva.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzijwnmg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itdqjolq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygplqflu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdvkdzs.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2huztious.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkddlrk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2etsebofn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yssdgjxo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlhwjka.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjjwczj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xidcdrqr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyoapiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jaipunbl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2joopzvcd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkjilao.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvltcock.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkazoyl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjhvsoq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2djehzpyk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwnajcq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ujktrshz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeysodv.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2entfotru.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xmclykma.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnobzyh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyphqhyt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaskqrje.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btbwtxie.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgxmdey.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxnydvi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2scjavium.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjymeezp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2memxfwps.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzdzmtt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2intaqvlk.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvaffko.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsxzfcd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyjhkhs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeicjbq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuizjqz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfmxavp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmjubqj.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2miyxqnhx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcpkvno.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2njgizomr.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbkhmdi.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnorqlkf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiecmdvr.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfxudkk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbzseov.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2voajakyi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2vihetmqi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjvgkon.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hthkzmpu.html


<!-- 参考信息 -->