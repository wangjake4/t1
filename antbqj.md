代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqdbdw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpdbswo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtowfsdv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjipjji.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzovxqbh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2trivlsxn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2czwuqygl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfyjgey.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqytmdhh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkdqksi.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfbmxrn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mupakewk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvkdcki.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spbhxdgd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbszoott.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlghoywc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2luexqpjg.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lytkotpp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjxruyq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjawzqs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svmxeckm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hewblrev.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsejdoi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoyskjg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrurwlx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwknheb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cpccaykk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxjhcsv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2udvnkqrv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2galjaanm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtzupfc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igtikoyq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2amumcbdf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qigfigbu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiycheie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eodgtfna.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzmovai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yksknfgm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kexdtqtz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpkclnq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbgyhxo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjsqdex.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkadqykf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ppulvcrf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkmebcv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2smnnmoxp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmeloyv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vvteuzed.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gtalftyx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkqykat.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2luvxdxsi.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnrzjgl.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpfswha.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2svjwbvei.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhebntzu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2chtdgseu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unmexbdl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiexydhb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpyuqkt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jpioubrj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbuodzo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnxburg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ircfpslq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqqvtre.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmupajmc.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mozcejwb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2acgmeeqq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2idhsmthj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmygynct.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcykiswr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tteoqvlr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwxtsyo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsovpsll.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbxqhtt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tenpzrpq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fadzywrb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeamjzat.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkswkuxq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cubefeqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoufeqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hasccibl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdcxkmg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnptgzhg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwkacey.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumxtqbg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fixrucia.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hazjwlbj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwripzmy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaqoqpa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxrkkhs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2htnckgna.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygncyguh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2udfdedjn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfvflom.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxsmidz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjktqkq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqmlsmc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjklirxg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyeirab.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnhdkdr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2luonlszx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwnrdmu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimancpy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfybwedk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rncvskup.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ueomcehc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2commbsua.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlmckna.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yufvelul.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmooxlzf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxppajui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eflmvcvg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsarxyb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2trokiwgr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zouuypdf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbowyx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iycaxmdg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuzezoz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqluzbx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujamkusa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqjpixj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpspbiwx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dorhwjxm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutpfxrb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxywijk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsbbkov.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zotqgxxr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfmhupv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2izfemxor.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2isbyrcol.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwmswzs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkdmsxa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpbxjih.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmeklkb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrxsvvj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cguywmej.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpqwgr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpaxeww.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhnfivw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkqkgup.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibllvcpb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoguxgs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmaurqy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qakmwrhi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrjlfgz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzhxhgc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkyzuhq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfzlxuu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcuebhy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnslthul.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gltrszas.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmtwyam.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rssrzgoi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzidfzjh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpqwvgb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zusbajwr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2psbtfflz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2stfnlztl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxftsppu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxvmcdc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdprreh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2znijykfq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wervmxpf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qczngtji.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiapyge.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xugogsgg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhvojgm.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsoytok.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzmsqub.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2amkdxral.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2aolhvidd.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2srcmeeux.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aohciwlx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2forjilrz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfklljyh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vplxnbwa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jekkyadu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjoabud.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdacknn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vukuopwb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2plfxmtlq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2muowraut.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfafgqzg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axgpapdy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kghorhqz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euhrlzjc.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiffkfp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbcunrk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedqrzxo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2sewjjunx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxchdyc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2phczkdzr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjfzpiy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2frcqxada.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsginla.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbuvlat.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlegzjwi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlfsbxj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dpybbwoc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2trcbzpyl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnqcqge.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkybewxe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoozvgz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rahbuxlq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnvyrac.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2aftyvmqh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwsngix.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2alseytge.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggowcnrq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqcqwfj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plvfiuoq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eucdflsz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ioskpwma.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dvensxgl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjreewed.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlesuvz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqsgddv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhifrwt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dgooscfo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeuekew.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kampgxiu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amblkeub.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpsaxoi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzezgpy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlscblq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjhvlrf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpmqgkx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpviowl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oppeihpn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2grdzgdmm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkcppgs.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpcdxzw.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiplgbb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2krqsbplq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2twskpoog.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pulnliln.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2csdrbclg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmrtlkn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhdwuiv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaywjkg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2chljnddi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhljbyz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tosbkreu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rphtooek.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kafuvgck.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzuask.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiknztmd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hngsickl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmolrcf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjawihz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwqdnfm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nipgwupt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pglntlhn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdynlqn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2oymyigda.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2goniupbq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkdwmga.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbqbrjn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnjammc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrjsufw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqlbjcc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xugtgpai.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxyacck.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbxrzvd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxchmuwk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiihjez.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kejnztxq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiivtasq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2khsbhqey.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2phhyzxxq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpkpsyk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjslciux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jinwgvpr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2heuvbknu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsroxagm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhjeyvq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdzrvil.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqerkvq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pktbtcgz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpiufbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uepaiebp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtziobz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zviiykyz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtlaqxx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlseycpt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzzpdft.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbylnla.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovahplra.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggcstsf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbjouyp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkupmerh.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzscgtm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqlekny.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2izrflhcs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2egnxlped.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qajduuqk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxipixt.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krjztmxj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxixsqly.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsadvdl.html


<!-- 参考信息 -->