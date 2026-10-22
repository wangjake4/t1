代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2igvavdhe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzjieex.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgjypct.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2guovcvow.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidsopy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfcnrsr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyvxwqt.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2bddkayct.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2doahitfx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apxmpxdb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2adrkylkz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjndxwkn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwhyjya.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfmrajw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkfubfa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2enpgjwqx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uelqybgc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kwluzbfw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bstdvjne.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmfnxey.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjpgtqa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2keeryclg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwujsht.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbjwfbk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mogfkkpy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eszisoor.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyozdfv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrviziq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbctqwr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbptokzs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iohjpojb.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdzhylq.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcgcywh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkedzydz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2viykonwy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kcteklqr.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfxyoqr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dbctmbtg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2owxrklhj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awoygjkk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2trdhotrj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2suqhwdlf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpqeycp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wokhmwjg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjcdjzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmdxotj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyjqfqv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmhaosh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmtilfr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2edpxwnoy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxxjseu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2diiqsdzw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hluzhfhx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbbhxgq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxkcbk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yseqlmzq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpswwun.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvuhmzg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjcowwn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcgmetn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkumlyh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcsfaim.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lujkvqyo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwrfvxu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyrdaug.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jubmgosm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbiocke.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jeixcjwu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epmdlwtf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxwumh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mawjqegr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpavwrke.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeutlef.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2svalmgel.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpuonzl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvkxwui.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2evenjgek.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrchugkb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jejciiuz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoxthoz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrwozxq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2isfbbswo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgajqib.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iogaigdg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2plaudmru.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qserjfig.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2imkgdmcu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnuvslr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2baqjtyto.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ermmmtju.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefoada.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vawkuont.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbxmzcb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jinvwgko.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjldlmqx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzdfzvn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdoqwaz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szipoevc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzfqpvj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiqbftl.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkpuwgh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqcrett.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmlylzn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvmmehn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pexlzraa.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shffxxml.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwgjxhv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvejrlgy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpwdfvt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvtijsi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoynguv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijisiih.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmasrqpe.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuqbzce.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbuevu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eugwfmxj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqtmrtj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yktdznxt.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2euyphcci.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfqdwcm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvsjctq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqophgd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxbuikz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jikmcfni.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2savxechn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbwduib.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yctvhdwp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zecvazxc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mghasluy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnssxiui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevybcnm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvxhpzz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzbjasg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2alootkny.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtqtlup.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbroplh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjpsqns.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2deagduok.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlsuqsc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zanguhwo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zumforzz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvvvhqb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfsqpxb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjtwmrv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dugomssu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gticdyqn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmxxsqr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxywhha.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlqzznd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqdtxin.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2awakjwan.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcfmngp.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxcsjqm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpnipyq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lleuphvi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uudotbxb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgtcbef.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhzeltd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlnbyka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaujsnyf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gadxqcju.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdxzymr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bferdivl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxglfgog.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cufssqux.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjumcna.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uolwfopm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuesnuon.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaxgqqm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmefskt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkviedd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlprtde.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jpukpwub.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiristc.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2detdpnfg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdulpct.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjtuuvu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbleayha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2naxujqwa.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dspuxwld.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhgfgya.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlfwwzq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsvyqnm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwivrao.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eluusuzf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykvahvi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rddfbgaw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iiznpslq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jvigojqv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaghvrf.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfspqdd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2opkgbthk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzspxfsa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsddrshk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fszrvrqb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbifgiue.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gobfnurc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqtcpjc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaqnexd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2trdopnge.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhosnoj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfkvdyc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmmjrps.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbvrmrc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cotxaczo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxgvpim.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bayckxvs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlykuoxy.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2twbdmcxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2albpmshm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcejnszh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgeaosk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvgths.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2edmzioqa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2swguvnvz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bixdpsnq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjrhkng.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuhzffx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaiwsws.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuvwvli.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2blapqazy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuqmckl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsvqwpv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qmclkypi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bketrzjc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2gwspauxz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2niubtjhu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ncellpiw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2afwcdcll.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomwskoy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvbgkuf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbypeld.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbjpgzx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqxdzrc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxtiqyw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2guqhyjbb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fykviacd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqclsna.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeqptid.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwwlmjs.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2epgucims.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2whfyisqs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ngghozbt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyedkioy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uaobngtn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzapiat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbgqdix.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgibwx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sysjwypn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttyrmzd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbyxlsi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdxqekv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzupctnn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xelqculq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqdsklz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzorzhc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwhpvmi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeybfvik.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kciakkbc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbtrtsm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsomtolx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhevunuu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsyuwrx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlpzyxm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gzybwici.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zykadpxt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcquixg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bamijath.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcecwxsr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sezgleaw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrhoisa.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdmuxtg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrghyyo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkeadxn.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvborfjh.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbvozeb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjkywfh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyarlsm.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeahuzkb.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aacjjtrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pciupmxi.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcbegmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeljgxg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuzwveu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuvcxyz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfirekzz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkjhkng.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnxqjc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eonzsati.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2livbutif.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnlvzeb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnthjmy.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvdqwau.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvvhovm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xprqsirj.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdstchas.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjqnuwf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnbcjin.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnxrabv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvxfoaq.html


<!-- 参考信息 -->