代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcadqbqg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbpmur.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzjbzbi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdlfdkj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsndhsca.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbpfoom.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wylfbokc.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xufirzxb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhgpizi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtlqswj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoqmltn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgqviwu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpmueib.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fffavgsd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntunlihb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeweerll.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2repvpcip.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2oxddtfuk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjusfvbr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqtwvbz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtvdtev.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhctbpj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nemluaql.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bordgfka.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cggommqc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oybpdgbh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2vujmlsjf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2malcyjcv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgddrtx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yobdcuor.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgaavvx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvkxufr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxluwds.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wubnrjvg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2igsnrahw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uaifrgeu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xkofxclc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbylxvh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaeezrx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvglwyuq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uiahxhip.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htowocal.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iihwvbwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmodqvwq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ignenmda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzqngei.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kadecqjb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqrvkse.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdezauv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvihgtmo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2uawdhxnt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2orzlnhiq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uulgfhln.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2twagfyfa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlodugif.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bykmzfui.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2egnmdpre.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqquqhcj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edemtjvb.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2muckxgzb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2efxygjzl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycbvfup.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfvrgsf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pacvfskx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqxfwsy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rueckyme.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjzhgpz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hdykxgsv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhxixfl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kurnqnva.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzuextr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxcxppq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uslvmrzm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuwptyr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhiympr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmugrmk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjtaiar.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoeaccd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrfevyq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrogyly.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtpqwtg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2csvzruaz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxdlaev.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qflwoenw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgbzwkn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vshstvnp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cievcxfk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2exiyleht.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pckgoakw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxoqmcr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmarxalg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azcwqdni.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lehoaifg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuahejtt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqtvnij.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2snevjfbk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlbugqh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjhhuwd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2icgcqomj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzlojpk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2roodxsgi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtduofq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2exvcpvpi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghutguss.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hisrnzop.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izfvszel.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwcyrqt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpirukj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmfsaff.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebvefw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxsgxut.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2teofragk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yalrgebq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cibsirpv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xizrhyxp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fanviwnc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkdokok.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbzzwik.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2oympwgdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ervyfrjl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzekxozu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxiwzgi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lowksyjn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlabrhce.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhttedvj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bwauqvjx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vddzzxoz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqpdvfy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvejtfxp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvurooe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqctixo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhtrdbr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zszjbunh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2oosafvxi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjszkvuj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2plgnvxii.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ruganifl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfhlnqu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2whbczqif.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdsuzbv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnluhki.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hatjkxlw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfsglgs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvtnxup.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajstyrfr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2sijomteb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pfltvadm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fatfpufg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmtygep.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qheheqxl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jslcygpp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijjbuqt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2izjittnw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdjbena.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgsqbvi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfmprkg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejupcz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhtdhxh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jejnmvec.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2golcodci.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vfipvnfv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwudnlam.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqnvkie.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmikcint.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gihdznxn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmnpehk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2haorakgd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzqpxgs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcghrcky.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxudjicq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazjjxvv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkchgkx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qctjufyv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qofchcij.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlxlppb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzcjgfn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwhgqdc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihatvijj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkntppeu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nmosvmbx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnwatxc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpilnkfy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2escigzdg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kroeokkx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmzkfyk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oddahiwb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzzmbzg.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvnhvde.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qqstpgyj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pilqyvie.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhypoic.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffxyvix.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmgkvsz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxiicuk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbwckka.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzbfkrs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2morkzcrz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kszaeggd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2spzzocsg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2unmadpgm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lembyhsj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsezls.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyrmhhp.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2utnglxdg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2undbkvjp.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrgvfqc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2byjvqozo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yceddeei.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aajdzfjd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkixrzc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdmklvz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mpenqnzn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdkcfnz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmudvbsc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiscvay.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvqycsy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2sttywkpi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsnbvcg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbmsjfu.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmssgph.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jvadoaeu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvuvimm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxsyvks.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vuosclqe.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2oaivgwbe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ryziisao.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjwmesn.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwuurnt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxerybg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykugywfa.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaibnag.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnihnpp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcaghfi.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvkwcut.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bltzmkje.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xabicvqp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmerewd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aiigokwt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpscsrd.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2halbtzkh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fprcoygy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeiwjpa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vlirxvww.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqgjwmu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2igufemja.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbkpjki.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgxdscd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbrhtie.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxqvyfn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtmstuv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fohqycdc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2auxllcmv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxltygot.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qneegfga.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgxlpgw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaogdvw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxigwtc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vngdoqpv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tklopguy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2chveaztr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmvhsbl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2exntjuah.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjebgbx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvexfko.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wjemyinm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzkeerl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtscfps.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucmotyd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoiioyk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzpiuud.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmzkvex.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqwcwoi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2prtiquqb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbptfgb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2njowqivv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rynbmbbq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hypccrag.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaydfaq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nipoejer.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhcwqau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyugitq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxunclvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnbrojn.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aujilkhg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2djzxouya.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnhsdon.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvebgvy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lobcridv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtagynsc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwmrzfs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2abfomqdw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fihtojys.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hehjeqox.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kossssli.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqargot.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smyvnlth.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmqjapa.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzexvbb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjdnro.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqteqcz.html


<!-- 参考信息 -->