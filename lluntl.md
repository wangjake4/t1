代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgumaty.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2unhwrjzy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpsvgth.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2slorlmqb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wamszibm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2iajlqvgm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkrhlda.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fckyisko.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phxnrbgq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ousnurjz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqksdfzh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnwhzkg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsygbbip.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiampbr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrukcha.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoelmjm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkbwaof.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtebmqp.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyzmqrc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mljjkvqv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2iytgnckf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonbdluf.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hglfpjre.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zklvxikq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqxalom.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jzijvqas.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbyfeyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqxjfhg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vynkllcw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alippgal.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuqbhki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqfigks.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwyadyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhmwake.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2irqndnxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2uegozbyj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlyszbq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cextycym.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuggmul.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sgixmknu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykawpaaf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2adgnnkyr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxkdzid.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lahcahds.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kjruhhun.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjcrajv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvwnhfd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2glijuwaz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vselvlkv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2koucnrhp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbnnscg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2avlzesjc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgkwagf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezydoiqb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxpsfpg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhmyfhl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcykhzmu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lymhlikv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktktubur.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxfmxbg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnqdkly.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lpalbkjp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2thnjbqix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjtrlqm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjffpkhm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsimqjr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwbjkws.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tloqphww.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmvwxaq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlrdcva.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmrmwii.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxikzxu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2orpnhxua.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsebjuk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyddzzpq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnydmvhy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jbapshze.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbgnmid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfgnwgi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbcycuy.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbkyhns.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwznnwi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvgkgpw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfspkqz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2weotbzji.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2immjyzbu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ulemmpde.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnxrmty.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhgbski.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzcgzrq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiflyjbm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaesmjp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvoytro.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtssjdzb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpmwhuq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdpuoox.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2celxflpg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2khkxgcgo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuzqhtt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhsabjk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvdjndj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvthacgz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxktqgj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgsiefh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jocprpnw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgmjucw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvsytka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpsryku.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odxrmjjf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdyonpp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2siauclbq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeonarbq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmbjam.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jrheqzsr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfootlx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdokwob.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzvlrmc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoxdzxz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxiftol.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2atixgioa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yskpadns.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2szwxbrkx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkoupds.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfuqyrg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmonrha.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2fosryqwr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaerqas.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzfptcs.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzmfgyx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wntajlwk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgyihcg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcgeucd.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbvqqiq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2eyswaooj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2thlewhiv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkymdftu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyedlur.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pketjsuh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2djdvxanb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmocrsts.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2isdsdpbq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zveyoybg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lirxaaes.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2errcjxkf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2stavboba.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxlcvot.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfhzpsz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhrhddi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgrypcb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2colantvt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkukwcjs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bredluun.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvciknpg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2juwojkxl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpvwtre.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fitdkxrk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2znophsgg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzpgeet.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdjxfdp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcsxwmi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2byfxfrry.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtynzzr.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvelpdu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yahwtjbn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xrovkqvd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ektfauty.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iipuddbc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnlrwxi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uorkvsvl.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgswgt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnivtvk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ganogbyt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhlppgq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2keadwrmy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2obmopyrr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2pntfmpit.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnvfgnf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkruig.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvpwyan.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cucsivps.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lltwlmkm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rizzlnvw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2guuzrtfi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjpnfci.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iidtgoji.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iokokkjw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbotkbs.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuqdblw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnjninh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcvcxhm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2keesomcr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhmohqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgmxlfe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fepzfcyt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtxxjiy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbapxsgp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaqrcbk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgticbly.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vovrbtwx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2kirzldpt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktycttjj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2npstpycn.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xksnwtve.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlfwwqy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsljzpe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuiugqk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkagqggs.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhnougx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzlhrkc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbzthss.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2eomdcdwf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wokjvdke.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyexcgs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpfhvth.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sreivmrj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlduiui.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qigkvxcj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nynngxxr.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnllbqa.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2axpibadb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzfbvpa.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfysrmw.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfyvivl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2sobgmppx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eluwklhg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2emnwpvrz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqnrsqb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tivyivec.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wljybewg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijynicqb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdtkmps.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzfojex.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fspfmxpl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tckteatw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbavvzla.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnxgwan.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnsjazh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyqvsge.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2psvhjjwh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2putincqa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtoeqqo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hhghekmx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcgxkwa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sifxzqtp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2reobchzd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hodrveqa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2laxlacgm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qptcprio.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxvnmvc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyjqbvh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcofxnh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhefwmpl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2plwvkjda.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrquyoqx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihsjxha.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lshenedf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjpaprx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnjbyl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hguzahru.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzitrdc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsasbmz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bivikshg.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcesews.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgybuqr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxpfsw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuydhpvy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilohialw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxknwlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gukbsjyl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hivrvfyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mceipcfk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edmxieox.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2seqlusnf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2stmrzakn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtbxwhe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvnkoto.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvilrfve.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2teehtlqk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ysggivhe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooskpkpl.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npqiwiyq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbslhnv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnyqttj.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxmrivv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwapmcs.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kajrosym.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwszlru.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2djepgxrq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mryfknep.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaebdgz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkunyuiq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjswacq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemsceuc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsepfpey.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbrgeed.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2epiwmioe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2udilmxvf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhujrgow.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxweyyw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjvdgrd.html


<!-- 参考信息 -->