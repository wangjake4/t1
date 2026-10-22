代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yttiusuw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpowrmb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2edfoxijk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoarcqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpozjcr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2swezfrtr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2nauanzpz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkkzcfx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzknrix.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgpfbnp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2czxnxpmq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdalpgkg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdjdmlk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umfkohsj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mikiojcg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwaccao.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqaswmw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgbanjk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjeaqay.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2enkdcvjw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afbkxlxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdurxvuh.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhidgym.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rzformxb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vcefeejb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxqvmoj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gkokvsjt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlzoxdl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yufkoaol.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwemlyw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qvajjvhl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nucoeujx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlxbnnm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2excnzpsp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxggzhzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzjrxkd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzrnvso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwvvjlf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhkxlas.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjqhjav.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaxqdag.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvamxoff.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2minnejkq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwaotft.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzqywzu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzxrhch.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnftspx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmzqmaf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mllttdeg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2elqwskbw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvefuhqa.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnifbly.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2netpgtre.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvcvarb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfxaxcl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dailrtbu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iosoorxc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tryhygnf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhinqadx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvhqchd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvhndxf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduwckgd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjjykoz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bypyhidg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sczsltmp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbplusx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrsudyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svsainwd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpvifeb.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pknufjpt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbwumjz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjhbifn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmenmoi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2repuoiyg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwcfnva.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtigosj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuccvzk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgdfgqi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmunrrrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpjljru.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2idtyxyie.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lujjwomm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2buiwpjif.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpnprti.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkfzzle.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoyzswa.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2maaewtql.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xizzcppw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaofdyu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2govtvnkl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdxbrpp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxajyxbc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnutmij.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zdusaqtd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgudzrpm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tircevij.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjvmxcg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfojxlop.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2exolflnf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2erxgdfiy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjordyn.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rslnxvgo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyphaoer.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2teybicyv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrueero.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vivaakaw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrvoojv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2odpyhsgi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagmpbok.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzprikv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gznumuiq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuksjdq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaayyfs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuxgqsn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gomuwidp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxyjklr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pytznftu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmfkqvg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwutdthc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfnriy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpaqfsc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bguwsfwm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnfydkf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyepfgz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2trehzaco.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwcggwp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwbrvcb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2apvkaygu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2umtaqpcz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbankmw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mudlrwmw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhcvvjw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cncjifyi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wibqarsu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrkcmrh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rfffcuxq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mshmyewk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tztacoae.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiecwad.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndprxsoo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsbnjwo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgreeere.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2smwcrroq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqirkmid.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlojcjhh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvxskyo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpmjtnr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2barewkeb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaoyhwv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2havtvlsh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxntmgva.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgpcpyk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2scvillhv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxlvusy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkogqjf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxlaluy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2afgjibza.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdeaybe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxihszl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yusfxlos.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvinzfin.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2parhykxa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuvnucf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyqogxz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qudjuqyq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxvkxpx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2adhhilmh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsrzblj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nghnbwub.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvgrjzn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2hphhaaqp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gshjvism.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmutumag.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2idbshdfh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsophkeg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2opdgucyy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgbxgdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdixlsa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdfqyfd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcatwzq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2savqjjxd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrltegmw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dohpoqwb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvskxur.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcnghnl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrkfggg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaysvdmz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qotkpttz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yafmgjzr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2oeabcgsr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvlzndo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rwupykuy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2viuceseg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2uavlsbwk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2yentlwar.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqqhnsz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfhubev.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbpkesc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2fftydpvm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqevvwdu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ijizwfuc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwephfaf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2toloknti.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnjhdbm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuhjvki.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzalkwl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbdhnff.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkoxfky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2aetsvipr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2weyrtzvc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgwjfdd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvajabe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bljxolex.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqqtcfa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qijgkizm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2irrnnrfc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xzibddky.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeofugw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2glqvidbc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jquyvirl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikssdn.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmgluxo.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkugimud.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvcslxd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvjhuw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zalpebfs.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwyxwit.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwytibiy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brruyqwu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjyzjcc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enljpmxx.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxwvwma.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dorvidnh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqelgfc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjkdnoy.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bawjglql.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2azravzxw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxkgnjj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujgovmz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwvwmpo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmbtbmw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2koogzlir.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvdiwh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2seanzhom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzbtmks.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ygutmhgf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhaqmcb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrldnfdt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uofdqxih.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfwupqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rapmnusp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdwqvff.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2elrzmuef.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2lujoymjr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoviiue.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwidbeq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2coyseosr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoskdwb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiymojw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaxnuoh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcbhqhs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprelujd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acszxfjk.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzlawjr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2npjzdsfn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlctshoc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iloqylma.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tggspnod.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffexlyrm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ligmyvsp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wprxszeg.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsdctwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ostitepz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lehgfqgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2makfmafl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wskidfyx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhjfgpt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfhfeiv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfpyjlk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfugyehe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnizhzh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mryhadsm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bblbkfvl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxixjkzc.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlczlpv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrhsyfk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2leqbrjok.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsihzppr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeobfrr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knvcuefx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdovfcj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ordyiflr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtralfl.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrqyrzp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvifbfdb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlxvlrr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekpdwmw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lysxcifg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgfzjke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2seabgnkd.html


<!-- 参考信息 -->