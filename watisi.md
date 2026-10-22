代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzemezw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtjvofy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdelxsqj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvquzlzh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoeizab.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwsjmyr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsogpix.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxygqkj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoegszc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoyqrya.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgfzkiw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkuwhyc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzmfdcu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkrkydt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmklcjr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihghpvpb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnwyzao.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyfgoim.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2izibaeay.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2peeufvyq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmgmavg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpnxukc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjshuup.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wzblqqkv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2etcfbjzv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2leoypemh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrwnxen.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hplfophy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvudnaix.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2duzgnyzu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2auhanqcw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtbfohg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnxcmrk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rymsjqqw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxcljvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsakhia.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2stunjmzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcpcczy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzzhttf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvqyepc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2elaiawnw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyetihz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2prjdzjpj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2yawqacbl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrneygd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mweespfi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2anwkvaov.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kssqjrye.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2odgyetfa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2twimgric.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrvxxxq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeaxehg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnptquky.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyshbppn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjitmtmt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2linxvrle.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnicjzwq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsstmpg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwcreoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2scrzdmzz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxcnsuo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skqjvmaj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfyriik.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrysqqz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2psecopdy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnuigxb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfuaxxo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yddoxdiq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2nroodagy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2buhzqgnx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2afuybzpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgwpboy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzgxdfh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fczbeeha.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iquudxzg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2amewteis.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbelhcm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkydnvm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyskoqf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoblfjvl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wahnniwz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gikqrivl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuefwoz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfrxcte.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfxlqms.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjbyriu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nidoduvf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pnchhsqa.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfiuwva.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmxhdcr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kfayavqp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrsuxol.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtfwqxe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnednulx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyclkjzn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrffmvy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2prhiabqg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qllecudy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsfsrxe.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2twirqmam.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhvsbai.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbdlquq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmzlyza.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzdwrdu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmkkyyr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nashjasp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zawytpns.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgzbgrx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvomsra.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxmddrz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxthxhjw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjfzogn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vurzelwg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kauqgkfn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2urupiyvd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlgdfgi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqmorlz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2updwqyps.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhmujup.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpnkcmb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmlsogx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqrkupq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kydkzodk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzuovub.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2twgxlpbc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pnasytdy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyqfsgv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzetmhj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xumvdrju.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkftpzuy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aapeapia.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbntway.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2abgtvjro.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyirvhv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohtqrzt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2otgnliqj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2auruodim.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2knatsqba.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbecjms.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkuwrxy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfpkhbo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwfmdcf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyryjvn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2retqzlvo.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yymgdaey.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeexpin.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2eitpysdm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2clwjggls.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwbdzax.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlsxanc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2puyfbmuy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrouny.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ynenpnvf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfbwwyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsygsrjw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdzlmdj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyetbbl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbofphlv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpvewqp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekpblxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpvvyck.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbizcwu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrjqczi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2julcozgl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mxegfyvq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eidjmvyc.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owtdrpgp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iryoinyu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2swuyrpnn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvaxdgv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwdmign.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hmazxycx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wguqaeqt.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjjxkiy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emgasbht.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfylxxsl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmbtdpd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsquecgd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhjosvy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuqqmdb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kngafgrc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmelthn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbtjfhb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnqgaza.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jayblczu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnymapid.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2miohnidy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tikoutzw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqaigvz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdlggss.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnphormx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2urogznuz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmlrjit.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcobhgb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdivkyze.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhkntur.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvktteee.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqewtys.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cahgnrpz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lidcuikr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmqniqf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbasvkq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiaauum.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zezwkjep.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhhvmns.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2yckvjfys.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnocfwq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkidqxmp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vitndskp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaendpxi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzcofag.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2karbtjxw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjyjphe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkyfvvz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2taabvtoe.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pmquxlui.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxxsgmh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2czojzmcs.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2laskxkbx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gujlvogs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wacbcbjc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpmdyvp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnppvhtx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazctaoh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrfgmia.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgijsdxi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikwzvdn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtjwkwg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplgvdre.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pnybfkur.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvwawsk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2umufamxa.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtkhtro.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyufqmto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2gulscwgc.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhzpjiy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkwsxkx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wykdrdsz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrsvglf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndorvpy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvhbos.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnchedfv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2trfplvcb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kghwhtbv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aunnigoq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvssewcp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpygejcs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gopxeevr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaggkle.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubokwzjj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fweaymqr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbjctqc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeddrth.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bakhuqjk.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vyidctov.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lombhnvn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2czejfzjo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehdwcye.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eipcofab.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfwlkan.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2unmoepbz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2puakcjwu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tozjldqb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvqtvtg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmezkcun.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iogeoufn.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nulyukuk.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmmphea.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cikdxfkw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xivnkqgm.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgeprgh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxksnzdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnwhaxz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxvzdlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdqtzzi.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrnpbgu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2huvpffqz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjolkkbd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2isjwjcyp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgzbmig.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jftdmznw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2extbramk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeoaeuz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqcxadf.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2duuxupkh.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmcnla.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkfbgjc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtxhfdc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvyzogz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebrktoh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2huycsclf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nnllnbxa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjoebux.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuqbgih.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqxihn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsxwkkh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubgebrz.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zubnhnwq.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxmgkem.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2mhylhdni.html


<!-- 参考信息 -->