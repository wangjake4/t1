代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwtetoy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlbplcc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lptplibb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjnzgjj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxhnmuy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqzlxvz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2keezpayu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjzgpim.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2giyllhkc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvszdxoc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzkormf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwlqohm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsgvbzb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvpxyoo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdtmxbt.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtfdvpb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfpgqcq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2unnzpepu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2quagvjqi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqxhalv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ieccbxzj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuniafp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyjcrgm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2didmraii.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2exyyakfq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbgdjvc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdjyfka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puoxmvwl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmhmkea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjfytsw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vczyzzhh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcfcxrc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gldmhqgu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yotjlvfw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoatbpu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpfegvq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdbpenv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2awoegrjs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmuypg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfnvkba.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2olunmwwt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlzdfei.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdyncse.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeihnlwb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuyqbru.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzldfbii.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbdkfv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgknpoff.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tasapbaa.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iztznaex.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbpvogk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgdclyz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlmbrhz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsltwwgp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qotzqcap.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tronmxxn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsiwttr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2artyorsq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmitqjtu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzocdmb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yscimddb.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxxztje.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuthqvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnldfgpj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqypyew.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqesgaq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyflwlj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nulvfjth.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2usxlzxzi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrscaeep.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2onvezbld.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkipyehy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgaukex.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tozruary.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hstrdhei.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuocilo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vutlntil.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaccljjz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltljmfcv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjulrbx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2civzyjpk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2houflqbq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcwcoer.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfdruil.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmukjmw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2izxqzgfp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imphzvmu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhgyvpl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqbhnoc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuttbmn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlijzuhq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcairnk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlujpzub.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2buuqxnqz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjazzjjo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtqqekr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fguzfcyk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsdveyr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoshonv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywewrqsj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qprlaswp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzpxovu.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bztejcco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhrhtnu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjtedis.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2axbjjhrs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqarjvzv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfxzrqo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whxasswt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyvobum.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzmlwmh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qncdflpv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbdtlwn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexkanbg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxoiamo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldtsymk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2obmuuzmq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dknewvrm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqswsumi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yolpdgzh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbadiiew.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgjjstb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdstjwv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoiunsk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdtmggc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcehmaj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kghqstpq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ketkvpbo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwfzjwg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2regpbhnk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmhvqyx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2meatjknq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfdalsa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2llqbpnhn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmyskwo.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zajqnoym.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsgridm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cueularw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nytgnsvm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpeuemp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cttjjkqu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfuhkah.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zghbnvex.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtylcyh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2youoelib.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdesrljh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2otnhkqcl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrxnjsf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjwyivm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuaytrb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kywwqsxp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izffwfxa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2awqldbnm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjlymqp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfismin.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtbxnpe.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwxizvo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmprqee.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lutclbvt.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxafxnz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuwnupz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlxgroq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xniezhdc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgqicmt.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbngfcdn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytafbhui.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqmcuac.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2welgfhwy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzloktr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yatrhxwe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2imtobziw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcwbgnu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqvqbu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhargxi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgppvfm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utffcjet.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yagwagyy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrdxkqs.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzmnyd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2egcmjeem.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdvkffb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvvltdr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqafxfdc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmdrzap.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoyjomf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2omlahzla.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqncnlu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2waxzwrhg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlohphv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrayudc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmtlmvj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbhsrxv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nkztsnsp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2henwucgs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiwsgxy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbkzqpu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxobnfan.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxwafsd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2albftqod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyzcfhz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrhqvud.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdroczng.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyovizhy.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfmknyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfhgans.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbcpagk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxrvqgm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hnimrvvr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2sksboopk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2flbrxitj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xylpzyfa.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sghovsdq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzamrbw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owyzmqrx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nunzmwsh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdchelpz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwvuyds.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghogsoym.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimyydrh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsturru.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzairrx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qodcxcyz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrrhvhz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wpunzgse.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrclirjq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvgngys.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fkliiocx.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgiflpw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpntaqg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2htslligu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbknmwr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyqsblx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrhwxdh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrrtfgk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2egnjghkj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrcvhkf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcrkepc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lddzdoao.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxplwfo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mftsaukx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqlkcjt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngociedk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvcuzwb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlxvgdr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmzboqo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhsfnwd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuvdegp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2csfzbras.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wvizywfe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwebdgba.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlzcauw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dniezaia.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjqfnnz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcqfqto.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohznpgfj.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skzzcoza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwupbsap.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfovgzqm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrloulvw.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoxoaji.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2znnwelxd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eokloatt.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdkhltz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcytaze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vokuxvkd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sktvszra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzugbej.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxblcjk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrsntav.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2afuvxtid.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyrtgfj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hihnlbpw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqniztkd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtppdqfc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2oniybyag.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vifopzhg.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evdjqlzp.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2januhlgu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2giobnmpo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzbwxwm.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfunkmvt.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgoaxfd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoejdus.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hswoheeu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlinombq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwswvld.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkfonlw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqryxerc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgyptge.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2opartorh.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsylfzq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwdmidb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2srxdyniz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxrzus.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsxayrj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbljzwex.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqctmwna.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcabqvv.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rolrsmzj.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2isfqrlew.html


<!-- 参考信息 -->