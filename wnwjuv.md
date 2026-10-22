代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmhjixk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fefjrmhf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoddbpn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjrkljj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlxawha.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiwsvup.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwreflzx.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2roxkyfsi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttzind.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuukemg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokwebeb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pivxsjdw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzepoak.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytgwss.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrsecub.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjagmdrw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlurswc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etcfiohv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2plgdsqpf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpcmiwh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsmobsd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzgqasi.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhsslri.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgcxzfi.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbaurcb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fturmmcs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnuhpxc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oalfjffi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjkyzhv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwogreh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyihauy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsianxy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2elxfrini.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqnpvdf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uifvgpsw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2yamkrqgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfsvtzy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2achjxiyv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdzoclu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgvkecd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2naybsrlb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzxeorj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbklvqoh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nmflnket.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2eezyjjcb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2elbfxzng.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2silypcgo.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjxooaw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnzetcj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhgoqpo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasgebxh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2glzusuce.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqtvwoh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsglfgvw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2flfnhhwc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wruwiblf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcumuqbf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlwsdkk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2seqbzkgd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnynynmu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxggitym.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgtrkqc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddivnmhb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfeneck.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjzpflr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfdhrxs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2etanazyj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsjegzf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqzkpfz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbztfgqn.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqylvgyh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfnabvh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcnwoyx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdchpbkc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2puuwwifl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2exzxxtpm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdonjic.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgqfztb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2liqozsgi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxfwsku.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqmdkfy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqxvywa.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yapsynaq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jixncomv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2febdodhb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjmexip.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrlgsyj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmvsxpd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpzgaun.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkwswwj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvyuvvt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwlhoeh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sscpjsej.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2olwhfxwz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjcrajm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbudrcjy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2awaqdmjo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcragex.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgxcfhh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2neljteui.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrvigti.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjlevde.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvrpbiu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2teadtwqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkbllwq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2odyrjppv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2uanmsmbb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aacqdcuh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2swgmqclu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevoaaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pytivxge.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cybmktrl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzraxxjw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2obdqvtyf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohokyhfa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfiiuih.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kecezgie.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxdeqkp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbcbdpz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzbhldr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnwrlgh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2avhdagsa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbydsukh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2osygdwuj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzufkxr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtdamlx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeadpae.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2uevaiskl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhmkpbn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojriosov.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfektfte.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoablrq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mahfyiob.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jolaghka.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dahjrfhr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmbzlxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpswsde.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2injacpyj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqkttd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjwqdbf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfkqpdr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwrekiu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiquqkbo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2blkopqin.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fajszzgh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqfoxmh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzermwf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzrrrql.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jwybphbn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yskszzot.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoonnpp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqagitif.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mczhwsbm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsxuyvt.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rakaeoqi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeymvqt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kywekaju.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvdgswb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnpzgjt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgmactd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjcxrby.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpicwtzx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2izejxfdd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zdskisht.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jagnecha.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmpuklf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ukojbzfp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nazosqly.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgidkxnr.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvoedt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdgrbeg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2psslxzzq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mntgying.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlevvvch.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2sarkbrkm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxykzhe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjhxrvs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2akdhhtkh.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyllemm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brdsbhkg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjxfnah.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgifyuo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iijvztbp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsyyfai.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnyqmjb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2sryxenjy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2lypofhvl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfxqjiw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vcreipsb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfdvidd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhgyqtt.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuxpffs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkzbnze.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlslvau.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwcpbcw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuvgwxe.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbfkjwm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqzxpqp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcaclnw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbsvpgb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuqyojs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2nefbxyxx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxdgqob.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2djayzgbg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2szyshgof.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvrbdbc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htecontc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxsqutg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2szxnysgy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhnfsle.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyumpclk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwlepeu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2oakhcgqh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2zuailjtv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjabzej.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pnskvtjm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhgcfvw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpvpvyt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvirttea.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zstavgdf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igmvpnqy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyvhpuk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkffnmk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2qatqniwe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhwbqz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuzclmg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inwdiliq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtujois.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2upqqcwgm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hilitluw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2woohgixr.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvvrqfi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2aozqhghq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldazncsj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2unmwlbiq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzffqxa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxavdww.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrokipc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfsglkv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2msugvwlr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbjadmk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2biybaskl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjshcaye.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kicvafrp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjdcmug.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyghjsrx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqlkyil.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2shujdrdi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdristv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyvpnql.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bupyekjj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2tafoghbw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnfrbmz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqyoilc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2piwfbuyt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzodxoxe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtvagcx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgynmugs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceubdmyp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qirmilfv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdcnbgp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jydjnajm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtqzdal.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pevajqao.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexzmzmw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2peootbry.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzwidvc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xusjjkia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byvlgpkk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eemvibey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjcauhi.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cprfzrmc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzarwqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjaldct.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2volhaurj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbuvgwz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxblicy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbdttkr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2thfknhrg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2emzojjhi.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zayqcsdi.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoepbmz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkctltbi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfrzums.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwltvqal.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnealstc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpmpeju.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ajisthpu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsklgqwx.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxjmadw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxdrrza.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqgthml.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvryfrcw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfdjqyn.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzlbixr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzrtrtq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2morxtext.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbauiwk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqdbgcx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2letparmr.html


<!-- 参考信息 -->