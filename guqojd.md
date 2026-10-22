代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2aigtxjci.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuinerw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbblptm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsghtgq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cuafiflu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bugxsknl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrrkspq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiwhpmd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amzjoebd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpihbdr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdnwpwy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2eveamjbx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ologggoz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dkicbgjh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnstxjh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrdnmdh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrajzstz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2haytxbcg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uavvwnkj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2isqmnney.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fhonbhhl.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knhtmbln.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2haothtpp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpknpjd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwywrdx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kndcgdfv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kretzikc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhginxz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fklnoszz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmiykog.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvucred.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kzprmdji.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbjproo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hstikcqi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzoimrn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czqecneq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsgqikz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxgfucl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fckfpwgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlwanbi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2caxshfnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfanjzg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rynvapqn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaitvtu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hccdfbwb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzjhapj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyfroxh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqyjncw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgquavx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbazjgv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2swemarxi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyzubgo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zrngqtry.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2unuzmvai.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2blqfpjkf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2msbkjgob.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cllzamfa.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rceqodke.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qknuxjky.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfnclqj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qyopfnjx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiprspqe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgihmryl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2flrqusoj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrouvoe.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2otgjzvfh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lekqhwad.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2piryftgx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2faojtibk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvqvrwa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdhrmbe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2veyvimrr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkosxwgs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsafrpki.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkufcknb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwaflml.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsklqku.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yacxquhd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2swbkxisb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqrorke.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2crpduyuh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2liyxtzcd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdslnegc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bormmses.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxokumt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrxctir.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzggpyob.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svbcilel.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzxqaus.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyryonpr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnefjvp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfhlqmp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2czgjhuvt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfeibvp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2isztswrw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2masiatbj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvrwjtz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbxfllq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttfmmjo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jluhrtgt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzibycq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yohnybhn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhdlceo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2equrlbsl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhqfjxk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrbhwcu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2giktjsal.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pewttruc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrqzaeu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2retuscyo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gufffslb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2orzzihgs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2maoxzipb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nefhudlp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hppvyaob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2azlejxij.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbctmjas.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjnbyyx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmylwey.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtriuhjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlvzcbz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mfixnbdg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ecimbahe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gntirrfk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeytwjv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtxztxt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqaehww.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyweyvmi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uabfpboy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2srjcdkyk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2helfagnl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcfuibc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjtlxiy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oteuuraj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2thlanmpi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlprobqm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jndjklts.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaqkkhx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuplodj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2frdxwzss.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyauargi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuuqzih.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hkywebin.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdfbsod.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyixuckk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pupgywbv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtwxmwr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2muanjzhy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbovpvx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwxuqez.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hftbzukp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmezkuxq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhcgkck.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvifsph.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcavzjh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiqtlbt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaflnkn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlbrhnx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwshhuy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvbpzjw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cazadsim.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oehpogpr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqpmnqj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiiszrd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hktndyib.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bskhvcrt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eicsdboj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2afjpoilh.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwslqkc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dixypvuo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2osvsvoeo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfawcfc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bztakmsd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuaqzbt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dayaqimk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiymgqi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbwfyma.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhpgcbn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqetolb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrlcasx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkskiku.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihbhljc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vugpmkfq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2netpyywl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmrocjf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxksfc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrhniqs.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjgebae.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wynruhgd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyokgitr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuptaue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfcqxvz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvivcooq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fryjcwiw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfayfgo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2abpdvpgz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aoapkaky.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwshzqp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2pezvzffy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ieurgmrq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuiuvtc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpleohd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2sftqqgnz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoercdn.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtccvbd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxnrlsi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqorormz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtdxzeo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrygboy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwspujbs.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2cforwvrd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmczldnj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2loyetkkj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2itbkntlp.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnitfflq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tffmhver.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2puzrvtcv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2boadjyez.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2uypcenvg.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqhlpkm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuskxeo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhgbwvf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qvigvukl.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ychldsfs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wldcfnhm.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gurndmzg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnijekf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2edhzhuzn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuawxcq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyefqqdb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynjvdj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfiswov.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whikgfiz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjznrzm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyfyfvs.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwtaxhd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rltuicvt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxhwwog.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbaozgm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvirbsc.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xystryit.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxbjaop.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxuchyn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hukrizxf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2idvjhgkx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kduuidnx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vblabujf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnxdvbv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudaxfah.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtbktho.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcltghs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwunmytw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gffqbuyh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayofkokd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgfrjyi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pigyorsx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsnojco.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgbqvbt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2qvleyrtd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsimbxzr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tzybmblh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huskwlll.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tptvqxzc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeqqdmv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrnlmut.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmgdycl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgctyhw.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqkaumn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuxdawc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qinspxpf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvqmkrk.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iydnzrnd.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvymyxs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwpjqjv.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwhjbnv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmquclvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prbeijxl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2corsbtej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxqlpuk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrtriqi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zskvasph.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoanjpd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ariqqfoq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rokrgmdn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2klwapwdm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgdchfm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2dmchubul.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqgzdfh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxttxzo.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnwbibr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjigxov.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjzegnf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xovcdfgw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2grtbvcyu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egeqceea.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2htwmucxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hapcwzkc.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvszjex.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2thhxnofy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2osgicebi.html


<!-- 参考信息 -->