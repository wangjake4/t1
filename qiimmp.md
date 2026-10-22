代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtlyxit.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ynybivrc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prjnzajb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kgahtqgo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mhphlocb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmszdux.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpnrxbu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buschwju.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjafgdy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjkclee.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrwcatq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlwdnnx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zexbyzhf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hkstwvrn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gowmssaw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdblkbnx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhibmmo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zotsjvor.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2enkjsprm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhmhbea.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnolizum.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucogtcsg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2iucyishw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2whklvflc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rucjzuda.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwfdsau.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnfjzed.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2agghpepe.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2orugxsqy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfubckpq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zirazplf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhopetk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcjpvqb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2piymwxnv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhocdv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woalgzws.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgeezjl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtlgjvf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aitjjnsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clwvnzdp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhywiri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wajmmyfv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrsrrxd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrvinmy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzndble.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zaskjfyi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvejvdqw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlkrtde.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhlvgue.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnzibjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpldiqi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtuydud.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bglvtapn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qldnsjiq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyywygt.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoocxfo.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnpouy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dltuwhlk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntinueuy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oikgixkv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjliioab.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcitys.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvvvzad.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cazmzjtu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlzjhgr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jouluvgl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsshfrbs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2humsjwzh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmnegew.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2julmtxij.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxssgdsr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwapmhba.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2aguwceki.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2teguhzkv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2soydiyqr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2omlxfxgm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmujkock.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfpxrhu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqktekb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhgoyir.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsyamuv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpozkbu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxqmzcq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdavbdo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2txbpshhl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2acmmjfea.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqswidv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thbhesgl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqccsyl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nknxcmyb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdtzeba.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eweehybv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzpryad.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aolucugg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2niiwugqq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgkpioq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxwehu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibicpuia.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kauyksmu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbalheb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bghlxyyf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzrtgsd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2epavtyxn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsplszz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvtnkds.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvuuaqf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccipokto.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2csnpkdcb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkskynhj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdsgjxw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vangphpz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzpggcn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tluqvoqb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2czzxpmmf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vazpgmut.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgxveqz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoxiwuy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dalmnzan.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwxxgy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwaunpm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbuwzlb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiyqygd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbouhvm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qflfzfdt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbxqgpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqxfhdm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamdswtr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkimxdqm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdfzuob.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgyjbzx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsijchf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdcpihs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyvxcbm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeslrwd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ensdxsdb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcbkido.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fshjfeyf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bldtkhwm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxczwixt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2spajloin.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbddagse.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkrpbbl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2denrjide.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoeflml.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbilocps.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsuwnks.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgkbwpo.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcohfqt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqhvfau.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjusoxf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvnnike.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhkijtn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgejkoc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlmrpch.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvgbfga.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oelzaaoe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mneclicg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tizkcdxk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvkbfxw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2otnafsgc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfkpani.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfidlyg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjwzwbl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tedoqybb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhocxjzj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbslrbyw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aohjnbrh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2phrefttc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2itwgqzdz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfahyye.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2efjhahfi.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhqdlqh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrboohvz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2gapvgfgs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2beitbayd.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lqouazbz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeyrcqv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhqcdst.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nijkdpvp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmtgygu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwlcxep.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrndprx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kottajty.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcxylen.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfrraru.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wispgymv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjnobla.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvysclyx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbslzoh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuphmbvz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuhojda.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqogqpxd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pznlucio.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfniebb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyoulld.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oemlmlgo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfspeyi.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpqkprm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuuzhwu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2tueixwrd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeyubgt.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzonowls.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gefinrdc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qazpuket.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvsoxcv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2objplmse.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsnlwjx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbjtnlo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vscjqvvw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mywoncse.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2psltrkkq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2thfhbewr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dntopbqb.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpnjrzf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwqjvrg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpneppni.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eibfkbeu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jhenfmto.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mahmgkhk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dvernwhs.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xoejkxek.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2txczfbib.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2otphyarp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxncnrw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdbeod.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvabmft.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtfhzop.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunpdnzx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxhojbe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijudrfeo.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhnutph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxbgryh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogjgxur.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknbfir.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrmntir.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2pafzswpm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgbkwih.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocebjuzq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrxqjnb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xanqypkq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2avmuqqqe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhwsuvj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2twzcomll.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtibhfx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2arsbjcbv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoprlzo.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqpyclx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2whozrpxt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2loulqrjm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwomwvs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2thljvtfc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtmtgls.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rocoeswm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmnymuw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbxhydn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uognmymz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aedkqizj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdizspc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnguykc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2cudshbpm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gxslyiux.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqcyajl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfvmvku.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzscxcvc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmuqmfm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozadwypa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvalgllf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osoxgyzk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgcvtjv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2faovcdcf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oskneifp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiqudcw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyppsrpp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvljwnkv.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbjhyha.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzctgotn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htpnalda.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rubqiagk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtiewux.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtdlpxl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2olonauaj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdmlcgp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cruabien.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2irjtluag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbegfom.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhgxtzq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpyhcfb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyelwcr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxrzgwx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrtlxkb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdcgggx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pukbufun.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofapyqhr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrdfrmo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yandxcjv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2veioswfa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvzptmo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2garchxkw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2emqyjdmo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqubytdw.html


<!-- 参考信息 -->