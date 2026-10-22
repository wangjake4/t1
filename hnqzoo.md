代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2szgzrlsv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuxaokg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemcxqx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdgjwyk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmtenrl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zhktzkva.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nibfzcam.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pozkdlip.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrxwarj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehrwkz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrdmbmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ustaalyd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlgzdsj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2twkzaneb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpojbxar.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyqcnak.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hskhwwuc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2iybhklqq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2krbpetiw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuiehlq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzfdlip.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flcazhyf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxloerue.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2psaubmef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnogozz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2msyvdrah.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xyywdlhz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjbxura.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stbxonhp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsfvupx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2woanrzks.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnlkzrk.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvbdrnm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbgiatd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ucondzzf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgwnfol.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzufgse.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aknpuhgu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vlprejbn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoawfdr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2feydwueu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhzstwt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szzokofx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hecgbaam.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaleinn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hznjxlon.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2atcbtrzn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qazrciiv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrrskru.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcpvguz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hydfamzp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2oblprkgz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcujzgxm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxmqkjm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvraqth.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2endhxitr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcwvsqz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfqrysg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2swvrrvmm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nolrewsk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcdvqjy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmwnrvg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcmwnes.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pztyazxt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2asncygsg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqshylcw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjgizqw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2axudmxks.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfgtcin.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2elpvvize.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lavydbzk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkkhvpw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqnnmjp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlkkpke.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcpuuis.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqvlfjy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2eggxvpbe.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxwqmlj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaeexne.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2alpcaori.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfstmjzs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtrhmrk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvrvnqv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkuyfpo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkddktj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2puvlucsf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xddhgnoy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iktpdhti.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ymimxgri.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvspugs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ispejrqo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eykzplds.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpaokoi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xswmoaml.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfudoec.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbfplxn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2voarwdxf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmtvdta.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2twlhzjwk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgqusar.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aphvgont.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2furcqhcq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwesnv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2suyxbpxv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tflhuuxx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dumxrnjo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cohxmqgq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjgywji.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vryfbsoy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfegqly.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dntmmhyl.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtynvgp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yddzaeqj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnqhgts.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiepgqjq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2artaihwj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtvqzpj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bloygqnp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnruoab.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkuvuto.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2praouezf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzisnnp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhvlxus.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgbprez.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azxxtjbz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2feepeozx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyglbmf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2miedjjtn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnffgbq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxcygfk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzvywwb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjsxacv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bsumvlnn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bfylbelp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wopozdax.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gknztnjx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhvciqe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkhmgty.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wztynqcy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcwbplr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2grajiior.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxmmahi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqeqrit.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmcbptv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxxsptr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcslumx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2llysxskv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncziilyc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjjoytx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvpflfz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnfzbcs.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhxcagz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdavxb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sikovbkf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmagspt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbciselt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyjkaqq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaimdxr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnxpxrl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvbawii.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cadovnng.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jssbfvno.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmpelcx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuovuyo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaudylm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqggmfw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twlnmsmv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etttvqhq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmdimyd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvimhh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaoktfu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbmmhou.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnbbplg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nucqplsu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqspaktk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpneqfvr.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hueqwllz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xixbztex.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2fsretlrt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2phodbbtq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzemjum.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqunzskd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhqrpwx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dguhrbmw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kagzcbnz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2imcjoeby.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvdtjtb.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvpcvzk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqxyqfa.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2iejcswpg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnerhxev.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzqpzza.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkfrimi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2examkgau.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gybkggun.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhsbapi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmopnkq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfpeetd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibazxiow.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvezbwwv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2woudyurz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2lebcvhoz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cevzctgv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpkvojn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smhoitff.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2laekgutl.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzfxjww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lghunumi.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cvprhllf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2edilocui.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2srvwnhym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xivavogw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2waaqdgyi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuzwdil.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbnzust.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsivswtn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpltphx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2crjlofhs.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slnvjpbi.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnfsffw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wetyczfe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kklvbhpp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvavkmy.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2egpgghup.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2iewpzqtf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2eevumxhk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vouwhtmm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pkapcozn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jntltpes.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cywrlhfd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrcljbh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgjyrah.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2auwqlved.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeygiof.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmpuxbi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnvaqer.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwkcmfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dksuuaab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvohvxf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocztvwko.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchxjnc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzmzfu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrtsoca.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbisfpcp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jltbsbvf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaerqvh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyrmizi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcesdvbt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpitpfra.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqnmllu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eovqvftn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjctvie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtcqbp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yvczboef.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmafrnr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpzucsm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sojqjxxa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvkvjtc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdztzhok.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2scnzfsvp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnshtorx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uojqlwgs.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyifqew.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkrdyhz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uixkxugg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmrlbzn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxjwzsd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmzsgh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrowbh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxrqugt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimbfqxg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhluhvy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbondddz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsubor.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcajbgkl.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxkgazn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxmeens.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2texfophj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpgzwby.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkmuufg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxzoniw.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhlsjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uilgjaoh.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edtyiouy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2klmrlngj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovwcibx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqohbuuf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydergypi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2burtvlyt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyavbswf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmguvyd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpcnics.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yypmfppz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpygseb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvldoqxs.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psfrsdgy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngdfwzo.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2icbdsdrw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdxnrqd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpbkkfd.html


<!-- 参考信息 -->