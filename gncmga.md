代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pytvpdhh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdhgkmd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2byvuroac.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqyaiwr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwonhea.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsodjhz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbbbtri.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkrmtpv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2embohtfl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjskvbs.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrodksq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwaxryo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dovmdyns.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwlucvn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rcolewjv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pckibcin.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhkmsqu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2smvdykbj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivumeqft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdustjm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjrqcew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pafkgpyo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxdtfwb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvgbdvo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lttfyccj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvfjegx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvquvvz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxzhygd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjvyhho.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrccnhf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxupezv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjudlcc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2pseoimkt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysigcbm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrngiodr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsertqs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbwbzpd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzwmlyn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovwhkvs.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aliyagrs.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2scsjcmxn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnsmayu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhdsbna.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaxmibi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uguchxds.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwjmftm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2osoqqqmr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaucwboc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhlxqad.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnjraeb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vutcpfwt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tthxdzlv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2btjuhbxy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsatmsec.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhzmguz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nazhxgwa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdxpjtd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzsmupp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kucanynm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rokmfdhe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbvkxar.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2evmgzavz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gczutjly.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tljlaawp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwgtlbs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgsfkhk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqecigml.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzsuhck.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szkinibe.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2psikdyeh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nswvbull.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ukotgcaw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkvpqfp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldtjkuv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2humbrnvp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zugapzdf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbkcvu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnysgkb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhfhpgb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rktbqzqj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgesirg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbivvgvh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xioqeakr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rublkouo.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2drylxtrz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2msrrbwoe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqnhzmc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgfqwjs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbzagre.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdexaqm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxwthjp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2erunnebe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuxncwn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvxmwiv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgkfyps.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2obqycpph.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiygzqj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2eurxmmob.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbdppyd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfmdpzd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjfrsmr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yflgxbmj.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjopkbsj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2azegkbqw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vroxsofa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awrvbgzv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlsyzjb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyszjpu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2usjemmxv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkubekz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmouzwet.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcofyey.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsyrutx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2eghhhczm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkzduhq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2aejnazra.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2btgmhils.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdstkiiu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpcvifg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kybkavlr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsqjcet.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gynkknxt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbyghne.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kznvivts.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzchqac.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eekbtdir.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjrcvgv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmhqero.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2luileqdq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuncxme.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cacxkkft.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlsqptr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrevgdsp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzbycv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smwpskml.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddzbqk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrxgmtx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msrrjjxl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfmvgqh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyuoxzv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2umxcszib.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2anjzhttf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfncdnw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjcsops.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vswiekck.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmqwclx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylnitwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swrzbfnr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gsplyfwg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2epxbglgi.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwodkoly.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xedvmnho.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoeqpnx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnmihun.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwuvsnc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gpocghpn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdikfqne.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2aeobhuwg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqdwvzz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gexdbbro.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gteyyvzi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxhynxg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkhvzxx.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fzluzpth.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwkhqmx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoykeyy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2palmkgmy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nokfkudl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zthojbji.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2izzhxduc.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2emxbynow.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2okszqzzl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlnikjl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsovaha.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2midfkkge.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbtnmqg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ikumdxiw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvclckto.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcoehue.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kosytnmr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2blsdcyys.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcwxgvb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2xihdsaaf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdpmxtu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2suoeedme.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnvjhmf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdvfhby.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmqkoqe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xadwztpb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzrifua.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiaqzsm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhnuxdj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ryosxeov.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pszxnzxk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidillyt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnlttbk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzrkenx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2povotrjx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwvzkno.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmummwd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgnitcp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjirogf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ajotwrbh.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nvearuqp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtfeeiy.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhfvoej.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amkwzhat.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbkhrqu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2suugxfjo.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwfljjh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdejoaqw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2veemlcnp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymfnucv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iokpmnfc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zydabknh.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgigezd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqnussv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifcyozz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdnhiog.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kceimshq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzdgwnu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjazdqis.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxeuwyl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbxmmnz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lokldwaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfcjnnm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvsnnqx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2cibvowhc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghqxqqv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpjsqsn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsstwrt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bctvjfkv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxxqgwm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnxarcw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyyvhxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwngmyag.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsgagvo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmokkjlz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fpchfugd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzqlzjo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2opwlbxfv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuhmozc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xncdmsju.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzrbvbw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2sycuffqt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpedjcde.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcbrdkr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsnplae.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiwyvmk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gluqihki.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlowfsuv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqqbucn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtxdgml.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsatrhp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfbivvb.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcztdlbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqafotg.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdphhwsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxmzaij.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxsmysl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ngotngrk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2johqtdcp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpuaqlj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxelsorx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcwyrny.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kleldgnb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyadbsi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2purbahvw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rieaihuv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2alesvgbg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scweizvc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibkxwor.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsuxmig.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrenxhn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2umhpfsxx.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vccgohxv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeticant.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nyifospz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxldqklz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbufuik.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcckmrdb.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvznjdx.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2efajgzqw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2cxclfozb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvemrkjk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnroelj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2jztqwapo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nizxrmbd.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjdgpx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwwhdvi.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcecyjs.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bconkzge.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oippimbq.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbiiaad.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvfaaxp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xuasniwd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2prkolffc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvmymcr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2armvkyuw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqnfcfd.html


<!-- 参考信息 -->