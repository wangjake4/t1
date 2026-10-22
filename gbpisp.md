代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzwakbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mczifxdf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cywwcdxe.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcbqcwz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbomzosb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fndbkuhc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgelvai.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaofsis.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2esjsybgc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgtouog.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2yemawbao.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxffyxl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brgeatse.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sscwgcxx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rivkpqza.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ylluclzt.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ienevwfz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkolbtuk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpaorha.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mddunndo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbzkoko.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcxhizg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yjidhthh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiskjvu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2djdapdwd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhkgnc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcztuops.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsuoton.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqxosto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeczlea.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtuajrh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cikxgkfw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlrstuc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2szugjhsr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fidttezm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2rbalgpuu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaycytv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lriwidsn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaglyps.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pddpmsry.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2iidseebd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xffrbtkl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpddhwj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscoszzr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaluuil.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibnzcqi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2syqajxxc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2osrbwvef.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjoinwu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqkdpwn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qudczbsf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfahord.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdowefog.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qymiooji.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhdzrh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uliruxgx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhivtrg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xughjnza.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqafvek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgwehrn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzssjzi.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2slofyfqx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxmtmvz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyyjvde.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azscplqh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eybfmkok.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhddwoi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsculpb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2twfzvvra.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2smfhvdjt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfmpznv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2swefjqmy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jemzjvgt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jefzdqbe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2drjwopnk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kinouztu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lktyauqx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgyoxtz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcvyiww.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfybeno.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvmozsv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2afechvjh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsypmdh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqjdaqx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvdoagq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqgmhdq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsbkloy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vospndes.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uavfdegj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2buaqdhtp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvwxxds.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xifryjrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfsovir.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2shrgwmnh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tygnhgbz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbrkxoi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2prjovqtk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zafrrspp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbhoaik.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlezymku.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpemuob.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqdbep.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfbcpmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2caqtrluv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2whckxssa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrmtjpo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsqkbnu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2djgvpsow.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzgmhhf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwmrbbo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xychvbed.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdvjhgn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegyuxgo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eljthnmk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kicgbwim.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuwrhhg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrgliak.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcefhblg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcnkoyq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ycasodne.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjidwxz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgjwsxg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkzrcjx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsdrzxf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjubbqe.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tumpaztz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrxepnp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrzokrg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sltdytbz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bedscaev.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnysneo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcacfwrt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kicyvudb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmicuqaz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dspbibyg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxrmlgq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvzdobp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2febvhaqo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqqsldd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfysxadi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evsppjrb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfizekis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjvygfi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swdenodi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gztiqvsq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylzfyng.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izmwzope.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfdakwq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqutkhm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthokarl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdovvpdi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjktdivk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtlwxgx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2auopeipi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfticmg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbiywup.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2scuubyon.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2czumvzkf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bitblqkp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrlymok.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vezpqstu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzfvxbg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2prsbknvu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2epwiowir.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojompvrl.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2uudtbelw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbwdpgd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bufbyrtc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhitmrjw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaasmke.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzgsxbt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2npkhzyke.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wlihorjr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2poemtuea.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kimzlumh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elajvklu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2enxbbuzv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gybjhjkv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzttnujt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2symknnkt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhscfkjo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2daqakmyn.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2clvobbuy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzxbstc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2varrwlvy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaobjeo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2oauudcva.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvopdasn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeyyxvd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrojqrp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhcinzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqknkqoq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnovbgg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2khcogdzc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrwmlkq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjhprz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2msixtapw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmlfpuo.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2sfunehyp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiybagx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2uvggpcov.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2plporajw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaxljte.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iamxszyi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqciwpib.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcqrypa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdyxaop.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfsyxui.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2drwrpsez.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2gesflqhp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xapjegti.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2exapgtgz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjppmmfv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxyzsyv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbfjxjx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apegqmcr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxntrds.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2beyjnbjg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibskbnsd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdqkciq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwpyokc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpzpbkt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpefrybp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyyrqey.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2amgjcmfd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bczlxedm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2snhmrxzx.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sulhnwse.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjjgrgx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzbqwwc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwacqmrh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygaemgg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrtwcug.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybqyzut.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvrwtje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuqlogc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwcvtg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyzkolf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqilnunl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhvxyky.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzlwtvd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmriwsqp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yocgcctq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrksczz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtviuce.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubapvdhj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gepzrdld.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmtugae.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkyodvr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwmitqn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlecmook.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjkavyu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbutrrlj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgsgrnr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dydcdupc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcevgbyr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ledtskvh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxoauok.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxzivpo.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccygonhj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpikufp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvaxkfi.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbrjari.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhfozmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btrdbyor.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gktyynpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epqrqogn.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inakswix.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqvqnln.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvqazue.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgikyod.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nokvqbgz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjypxwm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvtbabj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2gmruajah.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpvnytp.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkqvecl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2azopuqzj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2daedzcfw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpdrbjh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lognjzee.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptgnxe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpomlfp.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqtnpxl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsopylek.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsqrfdh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uoidjazj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfyqkbz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmzbngh.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkomfrfw.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2migziiay.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ayekbznu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiucywz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cirxzlsa.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjdrnww.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdkdjhl.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnrdhsy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelocmve.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhesaoz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2igdalizv.html


<!-- 参考信息 -->