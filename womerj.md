代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2defyrgiu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2uofzqoth.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2zztggfab.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjauepf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2plyldath.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuwjgxk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yahxwpcn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2uhknnmti.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2khwhxmtl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmergqh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jljkvraz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2emthurch.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhojrtc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwvoqpv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktagvh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkdnlbm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clyadkph.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ereplqji.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbyuqgu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtndgltp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxrkyht.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyeqyit.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eebmbpou.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaxpndj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtsttzx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2haibirej.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uajrvgiz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vufjjarl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwrvipp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2maslwutk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnljuhp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtmsals.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjyurjx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjclfioc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wtompatg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyapwbj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjzavvb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoqjulu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxmbjmj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fchunwer.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvsjcux.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqnfrts.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcegjmhc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkqyzvo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnubjky.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsbisrw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpzyqno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llgjqfhd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2edrlsnqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvabpgh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhlfjyr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfqnprc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqzmahc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbygsfu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2odhzapjl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgllbvc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fenxomfd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zenhihzd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2opvjkmjg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzpxcvu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2iesjvtzw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzqxhi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhjcszx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrdwbkw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2clkywhmf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rexwpmiz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjviruh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kevmiwuc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjkqohm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbiskhz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxzyipt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ehskgjvz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2virhcpmf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgktwfri.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvtbwdx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkzuyv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nibylclb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2grgrxdao.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuovzkek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdblluf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gylurgbr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbczzenc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hblbhocg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qquoidxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pepuuclh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qawcrrhg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njlrxxhx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwruqqb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjobyyrr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdwvwqz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whemjruf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiluxmln.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cvducizj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2stpieccx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dakfnmiu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtmjkkm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyaaxrb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoyomut.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jubtegas.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdrimfl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqnazus.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmkqmwr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfvyqcb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2aziyxpgz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjmqsqv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzhjtuf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfbwyip.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fukrwogl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvnggxu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfgavto.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecetirbf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyufgcv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eufhuiwf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgdnyrd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpthozu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2douluawt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaedokcu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtcihtb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtpmqvj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2alkejsvy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2piggygfp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpmgmvx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnogpqpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tscaxmrc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqgzqrw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tictdwyl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnpjhvy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2scipifim.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwusohqd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2umnobzci.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyidlwgc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jybpeoeb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdicqmak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aweiyfuo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gltcshde.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjnavkz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kahxgzwj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dviotfyp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2awungkjp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpzpock.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bfapqfek.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuogayu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xewjyqlc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhdmtbb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2twbabakg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqelpny.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzofgxpj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhexrwm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zomxndmi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqnbqyw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dizevjdg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfpzkcb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccynczsl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcmzzmu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjgrlif.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhpoify.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iumyyjat.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cukxucnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcspryp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmvzspz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaqkgov.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjfstmw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hptqncdu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uslrhlmj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmmpcxn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiupbid.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuixhfri.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkoiqgv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjvpczr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zduuvjry.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awddwkxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkvzbee.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvsqbez.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2roajgrtq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thrgcmkc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdebxpv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpggtul.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdbbgih.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbtztgq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbxbkzu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrgzlnb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2yazswqpz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2azengryi.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhejmhb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcshvyfc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pggalzwl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxzggrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqbxjxi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fstyaubz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwwolpf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2usufsumw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeqzqpy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wqenwsbp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2zltyksli.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkipufal.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugbrjwa.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqylaev.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slcpgrpv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkctiwxz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2afjuwgnp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcywchi.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2utyznjvs.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdynxyai.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpdsrqw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2itskdeqn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykumccag.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmdsmdu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kctutdzo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzserju.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gukyjuly.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2vcradmtg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrlmauv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjneshdf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjpzjqq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2eiifbusr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ikliogeb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jojxneec.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2xagnsnsi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbylilc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuotxivw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hytmlvfm.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2clqrthkb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pujqbsdi.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvvhzkr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvmovf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgqeaqa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2misxohdl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2whwvmvlv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoagxhw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2foncmavy.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuicvjq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oocqbdwr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwvukgu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlssexay.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecchkqzy.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinaksbl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmmuwnw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxilruh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvecqump.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2salaxcrv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwnoygu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhgdgbu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxathkib.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2taktfvql.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfzkzvo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2muinxbfm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2txzmfqdw.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rslucgrh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqvtmpw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2awxzkyeb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqlqusg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oudcnczq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdpszkr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrlkqdq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iiapdbbl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzozumc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjevjhbb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mniaxflc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjmgufm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsldslv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrwafcs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwqctjp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cycidirh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2odvhrmzo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nydpfvln.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyvlwem.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqrinwj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvamaurm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2btrkwcbv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgvevlc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrxdedm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoddkkl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsocbcp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlkgjku.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yagsqtmg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjkhhhh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkyndtd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazswxly.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vooeulvd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgsptng.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpcqyyi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxwfhom.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pswgtdsq.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2apucyvwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbmtgsh.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhpigvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2toxntlsw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssimmpnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2idqnnscy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eicamdgn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lquuzaui.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwfkffn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yknfccau.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkfuwiz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fjihtjce.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsvxrcn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gomrobxf.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2parsgzum.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdbywst.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzpujnz.html


<!-- 参考信息 -->