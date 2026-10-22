代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwplotm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxgvxei.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqijryeh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqomlbji.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjfblwv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvshtie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2klssnomc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvnhqkh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcnausg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2werupiiv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsltqzcd.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtusqva.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cycperui.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpneknpf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cakvlvqz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjixxhxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycksxotb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2snrkmacv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tradvwtb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pymlvsej.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fprpgqct.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmdexgg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2srummikw.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jaunxixg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qazaqrgv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfcjtey.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2segpdibp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hlubfyrq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gstgneys.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zxccvdxm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nohkwooz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoklmzy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaufoke.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziimkcck.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzskbdgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdnudtp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2drxbgsuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcfbvbv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwebiucs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2goklmgfj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjibthaz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uamewisk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2efpppcmz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwoqvav.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrpsgjq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lusxstvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2twuilveb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhppwph.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2eumnqzsv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2czbopyoo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtsxdsa.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eahrtmwk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzxhvjb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gicpzxup.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpjsjyb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfxfhrw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhidjifb.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrrxhcv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkrgzrx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrshgdf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgibayg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbkgtov.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuyqodn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmsizkh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtbgghb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cnilyfqf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwfkski.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkltwkum.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzrsyhy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwpdhsg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cllnooqg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnajusc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdqxfoj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tepzazni.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnrvaiv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2atkxkscv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrmltjp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yakzkreq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwclgzep.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmglcrc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2syigikpb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxocabx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwayfmii.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2brsrezip.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2buxzipmg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gddatczp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyienaw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdukpgc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdxnmaf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvopbxo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyustin.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tytkxmja.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmjzyki.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnkxagr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzzmtmw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzdohrz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cycyncnf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzasmhb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbonhjn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcwqxce.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2puptwper.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqznkaf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpvigis.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwgmwhh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmttdrv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwbwvdx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqlsbwr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zboumvgt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqcxqgr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2quwctmgy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2joiilgsv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyapfoo.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snsswrsg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2egprfkxe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2drlwdwur.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljejptbg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedexwfj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2biogwukg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmyyfzh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffblwjok.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimzryhd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwygsi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejidskj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnxtdhf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vouivkgk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2okciaeju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyrplth.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pojvzhpr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bhldaxro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrblzobb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtupcvf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnwbxgt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlhhyoy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2akyyfpcs.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dexmlenv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhwsbw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnznaxs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkjwdbf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmfbign.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqlohna.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtpmvwq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmoabje.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wekeblnm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vblksvzc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkawbsl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgytkgj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksajjkss.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlocojfz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjxvjtk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2srfbhssj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hssnkcku.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxuyfam.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pmahhoqx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2adukpoud.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehizlpnk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbxxfov.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzhnsox.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnencnn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoeozuy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrheyod.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oektmwgc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzioprb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmzsuwe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbbfqfi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcgovjh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dinukktn.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2agqnxcvz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcudmey.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfglklpf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2inehvlnh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfzqbfv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwnorpe.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcbcxuo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfrsyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2byfmprcu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwzqlff.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtxipoa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgkhffn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyondzs.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjvtycn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ekydhsms.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgueyem.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdsyqhk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2osbibrwk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqoqebl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybsnouo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpocwns.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjapvvb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyoahvf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2simoonan.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzabijv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uodgknqg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhilfxe.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2suftttbh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nztohilx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2obmfsoek.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpihhoso.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmgfuch.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2czvwileh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2csmknvps.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zlduvdny.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwywtzn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtivtcrj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2megljquj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyxhrdg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjirqdfi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ualouuyw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2giydekxm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2oaodwnfr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhockgd.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxucspim.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrivgjk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pemggsay.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtlqtlq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjflfdut.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgtvwto.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2hquqbgal.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaaeuqd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwcvozx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwsjnae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjjgfxy.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqlyblf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnorficm.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikogbff.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdinbsdu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkhutma.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxqdlon.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2crjisivl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krywuicf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpzofoe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2niobdfaa.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbepynpl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2szjzgdsm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdabgta.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2inrqssev.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oalbswqw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzappgy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2krpgoqjr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdkouin.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrovxqv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmefnlzw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvbmffb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sycdbywj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ttikxogn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pazxdkxc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2txztbiwb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2obxlhczw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klkwamjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwbvfiy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmcdalo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmfopmn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2thwvykpj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhsylnt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzveclpl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vnddjzgl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2atvvapbj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsspmfi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2heycktgo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqmsykf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgkgwxd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeenhlos.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrcizlv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqpuasa.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jehaskiv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qswwobhu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqqsdu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiyfjgs.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtonrzl.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsaxiki.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2idgjplmq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dteptgod.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzznucmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbhfmnw.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzyvuyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auhcmmqm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjajkruv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyrohsb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwcudij.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkzhcbh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcvtnhs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwfxjdv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nazgdrkh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ektswrxq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2btzdhtpb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuelhsx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2flymtjoa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeamuru.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqxxmmf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2loatffre.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsvyglh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsylfdgd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fncpsesc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2aashwovz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvvptq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wincfuuz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzswono.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qldmpljq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcrazc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgtmyke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2chwgyuac.html


<!-- 参考信息 -->