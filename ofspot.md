代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfecfmsy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbuoqdw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzegslci.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2phhtjzjo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzndsaab.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrqlgqx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lweccjtp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhncdpag.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdkkiic.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcbceea.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2akzotbko.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbblwuh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abnrrdkc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cluwydlv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bewhhhnl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgtmpdi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrdelbe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tniybjxf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqhvocg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqtcndn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqitak.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rieefiud.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mahccsbz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbswejfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2targtcle.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vefqrlxo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jbczrqde.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlrmhuc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yogcnnny.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxtilmc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2edetcmon.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrzckuo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dqritvqz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuoobym.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2slpshrkc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2butstmlo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xffawklm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpcpofl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqlbndd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdjbox.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2egivcrug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxgrzub.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wonnrttl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zbornjla.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrmjpro.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxfpipw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qobfnqjd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqllrkb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhnjfwb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgegayb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2emkshbsm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2drcwhukd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bipanekn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtabirox.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvgdkgj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvioxmeh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcmlawg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2chkrfjor.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbkkmpc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfskwvad.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tkokndza.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajizaggu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlhljwo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvfofot.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fclonlcy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlofpijo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tacwtnvj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcawzsoe.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtyekna.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vakieszm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxrafis.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2messhela.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2udrpghqj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzintcr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oggdtifr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2truufmpd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlotmgmu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grbedfar.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2opkyejjv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2smogobeh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsprcyry.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uphqkqqg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hugmjequ.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2szuretdg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmlfgch.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvtmhd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvthrcea.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhanbtc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvdaeyo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbmafyx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2elsfcbsj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2axdtuytb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpjfgls.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwvlxnq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tipbdhyh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlsqzhs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2caatkzgw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2idalhbck.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjskxwt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwlopsy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnyuryz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzcskil.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrbandu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2akokcbhe.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdkxbjg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxknpat.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbaobdu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlskybbn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyvbtjr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzzcqvg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kptvjbmt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2visglelf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyonaumw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgtpopl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yedmllhv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxexfhd.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2venfoyhe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbabydqv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgfshot.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdlwxlv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2laqbpvui.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dkacxhyz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtosulyi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgslodd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2saadquya.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyccotu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaulaog.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywfyyud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2acpzzuij.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2acepcead.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeysakr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2egkqudth.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdxpoog.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcdmegh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mamuwmrs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwenjlg.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2crdaovsb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uedvinxw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hihuuirf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpfaroi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvifykxk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jpngbvne.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjulpdo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyzesuc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxacggu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvpsnsv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrjsigk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcozqnhy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mweqxcux.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqqbidv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfgerfz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjxelbl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpskesm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jueprloz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uigavgmc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sektgzqs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hamtztck.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaopruom.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxclqmx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwzeznv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdqiiuz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2elpxodnj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvjkxjn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbloyvvl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmebksal.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xreockqy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vywngycf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnazjhyk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwaxxwj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sewpzbrg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2phkvmfsm.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2healddsv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlrcpen.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsdsxkv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iftspgcq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuaxkhs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2arfnjzrp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqrvaum.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsyzrhp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbriskiw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzdovaw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshctvcf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhwdnhe.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqhnkqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bozpwdru.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2enfrckxk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oatsvlyx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhujrhc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iidipjri.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kflokvzh.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tarkmkfq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujqlgn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkttzjhy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fefspcmq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzutordu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2juorrgba.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvrhqzu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfrnyce.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttujxtsq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2haskkaom.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdemstp.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pehhdxxf.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgmhbnc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjusdsvc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2afuplicp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2upatqpvv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgqhaat.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqpcglb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhuggst.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhxxtan.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2riusopod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhajtqir.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuzinfv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxowirrq.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvntvlr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhqdixb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxzsehs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jaezldbb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2salrehmn.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbbdasy.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ualrzqta.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpqsxcd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkqdnpu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfkjzob.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgpsgja.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibartfsr.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvqktqd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgrvtzm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpivxii.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfemgf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjrogth.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyijrer.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfgzynk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uemjqocp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfvujet.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgkgmrl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjabxxn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzbdqvz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2aubcghpw.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxmgccq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2plzwnvsr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnejehtq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bldzxowz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbtzcfy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxjuqdo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvplgnqs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxwcxez.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxtoiqd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwwjucp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2buzxmifj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xarvbnrf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iabtutnj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmnkerk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euoiskce.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2howjuyds.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqvouws.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzkzeos.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctjigt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbvwiox.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktctfcic.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeoytgg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlyubel.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiasfuqe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpdfxsc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzywvnr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzqpbcn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbieukv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvginzs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvicfuv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frhxztcy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2keggwjok.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwssjvdf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sovrqbip.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwldpjn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvslskug.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaspruu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvqbga.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epnzqtpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gomlphpr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzczxljn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxsdemj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbqjfaf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiwxbbs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2koiffsoz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjwvqhu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sztuvjxe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2iywpagro.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndevlvbm.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilufvktj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vykkjrzm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcxrzsw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsakronb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gppgorwm.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtthjzn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlnfkee.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2iuctswba.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xudocdaj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jptgfvdx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvjshth.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdkxlgm.html


<!-- 参考信息 -->