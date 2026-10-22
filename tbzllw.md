代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kewpqnmi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkexvxar.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnqnely.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piaqijtg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tenttqgp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhieip.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhnrstm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lywowznp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehveqglm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2osplchvs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eugcqgxp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fplayjkl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2araehhsp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpcbvmu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2inympizi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbfjalx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbliqgsg.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwfguqe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xlumvwcp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2njzfmojp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2julzitmg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdqdyhn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mikixuay.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hcblozap.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yapehcsu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmymiuz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2emxjppcq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2noeuxiby.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjzbfrw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pljjrspy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsnvzsb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sninivhg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsdzlux.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfufweo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrzgfip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmopzp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2sayptnpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcxsnwn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pncprsut.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcnqqrz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhodxov.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcmjoqp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2smwfsrak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwkccqr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcxoqcp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzcccps.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmgoqvm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpevhie.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnadfqc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtuyxzz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbhllrd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvejtba.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciikauiy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuztbqa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mednzmxk.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qshgzwjy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdhrexy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygooxtk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dabtgyjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zminufbr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztehhwpl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfebuyte.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2urhgthky.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvcxjnv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxpepru.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2icomdwib.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzgmsnb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrkoqhk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmffwsp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzukgryi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evuuoorb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeuuksj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbwmbqr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhrkix.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkofpwyl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2crdlknmh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtuueil.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjnjsmw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgecnbk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2feprfmin.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxlaxcw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbrhsxq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdwbshz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ncokqtcd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxguzvep.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmypcddr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hetmwijw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsphpfq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcscsswv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqkihcu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoazqkk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yszkioii.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdepips.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpflwzu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hauwimzi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cukehexn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjkwtgg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2casrmorp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhtkayz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhuocjv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdcfhwy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2stldsgqd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktttogii.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpslxeza.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuxprdx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2satrsixa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxahzuc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukryqpfm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkxpgyr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cktjrbyr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdvbwlq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzjazil.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqklyqby.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcxzmry.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouilkkdm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jslgoflx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbydxiki.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvgvici.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuqvyzk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqrnaws.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqceceda.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwylprm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyddsmu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstlqag.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2owtyjndc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2knmmktxs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2klqqhxtd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lembnqvu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnpigpw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekonvxev.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtdcjfx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdakuzps.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzxunqz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdybtlew.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvdvkpv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gazmthqh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aedqfxuz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2noyqbsgi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2edjinrww.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2veavlezs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvztthk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utygcsyr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzouhwzg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gthkuixn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnxpatx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgxssju.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvnwcqf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgohepic.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgfhqvf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvwzhda.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjayttuk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuetjwh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xpazpnjh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjuhngy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjrjahh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2prityyrd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2maasnfag.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhldmwij.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ausfqtiq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tskwfhnp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpflliie.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yegyfhlr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rplxirjm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eismxufs.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sekulryw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbyzfqq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2phltulwv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fneqhzkx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2najabysy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaeahxa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xmftkoxe.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bklpcbbj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkkrumi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvviikp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smorormy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mirkdtgl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzgadeb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgwmxgl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rintavuk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2zadqtfeq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxzrcts.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxddnnu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vztzleje.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sunibxml.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzxrlni.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifuejty.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llwiyove.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvwbieh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofdxvwq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zrppaftd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjswtgh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdzxhwo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tskjfehn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnfjnvl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zawokzbb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmjituy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqlhyvk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmeqqtu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gsneyeot.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fifkjjfs.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmntknmf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkizuuhj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2avnymzge.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2geowdnvy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrsayms.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgriphcx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2euftxjup.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjpasdz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2elnwzdqo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhobtqa.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjerkivd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwiwedk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ukafuqle.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2spitjmox.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlbhmur.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nskngimo.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bqniniao.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxfvzfa.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qeehnvjn.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqnpuaa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2thwambzl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzybasx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hstfzcoq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxqxyck.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnovqnma.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2inezjglf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbeslwo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hddyhewh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxpwuwo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2icztwcdl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaqgikj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2cgepcmkv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlmqudy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lukxjwos.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2emvcknlh.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jphxfjes.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2klueessu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgetyold.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njotrnpm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pytkfzmx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2trfwwzab.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuhipas.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbgpaev.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfmcrcd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfinrmzr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjyunar.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2noziqvks.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqfnbdk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnovwog.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbdixkz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uipgosne.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbiqceq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlbulop.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdibnclg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfafizi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmjbcor.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqiakyf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuybbss.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjftzdco.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpajqzqh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2knfdvbyi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkercgoi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpavju.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeykxoe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfdoowu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfdbufn.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2roqlktct.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyqtzdx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqxbfrj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlcwwii.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxcpbhm.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2weryosky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eexzrxbj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwjxgnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdgikua.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdlppaf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jktltcwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2smgpmkjk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2adzolzcn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzrkxlv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cikdjugv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfaceci.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnuotpb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibysojkn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shnfjhlt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xczkltwn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghslwfha.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owoxtfob.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uomuzfxo.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihkuxqt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owlxtfrg.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqxzjcw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2byxfsevt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqfqhcb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wyijkwnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifypzeae.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlaalfa.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmmxcpw.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqfepkk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzkzwwv.html


<!-- 参考信息 -->