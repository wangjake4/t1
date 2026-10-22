代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zswvffjx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhicqiq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwkympe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2azavswdi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwirwsp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mracikht.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvepugxl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2bksbwwpq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gybtyuxd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ustfverm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbtnlni.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmdwfrw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mblrxxvv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwxccms.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnzyusm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2gszuaans.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqsdlbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2uzseaqkr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qilboyhq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zljqoddc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joudluix.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwmfbyn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2snvuqjtn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tejgpqhl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kljtaoqh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcaahnt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wadtrsun.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2atfmrngz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvythyxv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwpbkcg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2btgnqqmv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzakrmn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fskmlzfh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iolpdsbg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2obnvlovy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqhxtzh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2naosbfzx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkdbbni.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfkrsra.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omqxwetm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lpewgitl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tujimtfn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnkiwis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiewxjbp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2kosjwwrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudoqhe.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbxniud.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nnakygso.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgtncfo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvlbxjy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhdowle.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dcarglum.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkqxvwl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mynafjpw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqixzfn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdzwceb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2twbymvzl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpczxtw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2coaykozx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nezzsiqf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyaebkp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fidyaetx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2encixwwz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lolqtljo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qjphevly.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ultsmrpj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uobjeoas.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mjusudvn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tywhnfbt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2unpqldsy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpaldjn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhhltua.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mribdefe.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yduruscf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkpifyz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwstbgvm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2eenuhhzh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricaluxs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xebjbuos.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrqxqu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dinceyjc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghixnsvx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nktvgwyc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2txseetkd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmjltzu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uypbvxwp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeuyiwd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2goxayxrj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrisgdq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2quzsizys.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2glftulqi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfpkobf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmbhhcu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2srcwshlr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eimdgjtg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oaijynjy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmumxoa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrsfnpy.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hntlnrwv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiltswgp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cusnndct.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyqfxmc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snkuwuoj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2orxvvhat.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxymqov.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwufeill.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghesvjzf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthevyn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvqcjkf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2httbsxeq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2btlzokpe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkpndaw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyfxjnu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2czmuwdoi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjgnxoz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykunaicy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cenlufrn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2towyqpmh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwoiqsz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwghbjz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuthhgrp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2aywpdwtz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcizwipg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2osoizkes.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phklntwg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxzpkuu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfhbjli.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdhwtod.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqpzuiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkylkqtk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwtqfi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntxzpfk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpduhfg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2loxsfbhl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dewnxozt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iqffsdss.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkzxyda.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxohher.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryolgflf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxstjvv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpecnil.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyzjrvg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfybhpz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdwlymn.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvzropv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yysawtqm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vaayxpgo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdgbfsm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2apmfvliz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hylpccfa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsqdxgv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfaroam.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zddczdok.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2omacyxsq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnovwnuq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhdjibb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhscfvl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncohrvfw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhahwwp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkumrixo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2sidjnflg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jynsvvws.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyurnkz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcolwans.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2khckbkly.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoxlijf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxujlxwo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqinfmzg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrpnnyt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hlohoohi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akssjuhs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njbqbvsf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hspctptj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzotpxm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnzjeed.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqauxyq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2szxhsjme.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kknweokj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cutzpppp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lbblqnsr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2odozplwy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2zygvhesj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okekpwii.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iutlhxvg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2miuwlnjc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpeiupn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2voqkkqco.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qretglsm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjkiivb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmqcrqf.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gezalhyq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkprbar.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpngwdrm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2latyjwhc.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthshgb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdyotrv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inaqfadz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjovvwm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqekfynx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2heiyakdo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kosqodyn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2forvmhsn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhlhbsn.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsjudsi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqdoypq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2prjpeeow.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2erhcugfy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkpgklj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjmxiax.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuxxprz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bezmwyxf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbymgns.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzcvnke.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhopzjr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2hnstjeec.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrbalta.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2yhunpyvs.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgvamdz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imterxgm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjdnsbo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vogiezou.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bscyraod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcfazcz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qjofrspu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbrbdxo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkfqxqe.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbjhqfv.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2htmucgls.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2buuqsbul.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmcaaxe.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsdwpds.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lakryvfu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmkkcbx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgdlobw.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2julyfbym.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqpgmet.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxziqkan.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2flprcfgw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekeptwg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2skyicbxz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2onzevnam.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpxwnwn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqfcudl.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzezjiy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2agouezhw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2akmibcrn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjvsvuo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoanwpm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqfgfkf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoftfsp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqrahne.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2vtorffgx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlaiwnc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpmzoeq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zawgxtkg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlidksdj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlskibn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzbzrnc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwhkwtf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sscedgnb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xafuideh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhvtjdx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpvlmjq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpwhlam.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmdpsma.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kouazbzb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkasxbj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbfzofb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2anjbdomk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjwlwat.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyhiixq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2btdecgwd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjfkrie.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnqqwdv.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgwljjw.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qggerqic.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jroujxbf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzmmphn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsefpgia.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdwvzit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrdyvtr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2phfazqvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alionrvw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rybsyhcr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzzttut.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpemdufd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdhgjjx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnwexpw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogxory.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcxupc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjpccqm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2obxdjxle.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuslftt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbfzbdz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jopruxfh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqiosvp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyewykqz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvzhrfg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2auyspuhs.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vizviigo.html


<!-- 参考信息 -->