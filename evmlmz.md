代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjecquhb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eclnlqzd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xofievis.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxpmgxg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnanukb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxrhpkc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fggkxfvf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cywiegqr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlbfnhk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoayrwmt.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdvbjqy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2icshvaqw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yxegrdzm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sezzocly.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvbevwo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qrshjbic.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mftevivw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2biraromo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ksasklxq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwcuswp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ysonzzar.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhaqvld.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgucmgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cotalapt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwxdqbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knzdveco.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pognhfks.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxuqgdg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjbloyf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjjyes.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqhzlbu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vsufgyxl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lteqbbgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pogwigff.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzauuda.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cihkdezp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kbstqjqp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyespemp.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmrmurh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khokridd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbytvlw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdgvebi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlnpjuo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcodjyve.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hirollic.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuzygek.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xihscytw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wejwxhnm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nklzycgd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhamycpu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2echobosr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ystydfbd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nacfzabt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjotvyi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilebuiyd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlndhmdp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqpscgr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkklxnca.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcngxvru.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mawozezg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwnthcm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhbqvjl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlrzylx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2baxagdzy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tykhtzzw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvmirtm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjytfiw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbznnvf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmviwje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nwblaodt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzknvndz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2phyxwpfe.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvifoart.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2juwoiuln.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrdnjyf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuxdcam.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbiivek.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfxyrlc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbgdwvz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2azvunsni.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2azqapvhr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2szeourmd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzgticx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuhoehy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmwnrpn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npravoxs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsbupdo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjhidnl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fphidfwg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsvyzmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjcrkk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2puklfxxc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvnvhfh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gksceufo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wugzaxfo.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhjtmdt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajouiwsy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwzqvam.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbmrdvu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvhaskd.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bspubyzj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzhqqws.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2paznqyrm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiljuuvz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhnsodb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oezpnpue.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yebuvvmw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftouzurk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2teaawhzy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekspzunv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eginpbfv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlsqsid.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qtodzixw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbajbhrg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaskvzb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uoikfvyy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyjkvjh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwgzbj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdnsdnx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qftnnoia.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gazpsqjd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqetfrk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ethmmktm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qldsnhsz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqsrafz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kswmmpro.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vplqrlai.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myhlmnjz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnxeadq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnffmwrq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nosqyhnh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvrdjmc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttoode.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypifhinf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgucficm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pihodnwz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfouhya.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqbdgdr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tczuaaas.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2blasaisz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdzxfjq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnzsih.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okkxpzbv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwizing.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2erypfioo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcujzah.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2psvelgjb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrunuqil.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmgdvil.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyzqhka.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdxjdpw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubazodhc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrscrtw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2klmjraai.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnutlvqz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yikxcmnm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmffqrjt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgmafmc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lprobbic.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfqxrok.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtcemob.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qivsewxv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gndlsjzw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeydtsp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqoteyh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzujatdx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrdpiya.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2hytlbasl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iiydyfkd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpffnea.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqmxbgm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbmavku.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrmfjqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tltuubbl.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2khcavpxo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzlgdia.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpptdyu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iphppqhd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwikosro.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcrhajk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgekrfd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmcjvjs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcibezsq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcudnqo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqtkigk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2abmyhjiu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxzmufb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtuuxhg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuahsiq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hptpzrhq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsvltak.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2svxuqqdr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnsgjtc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2igwqftse.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjqlcgp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktseiolp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nswtrbzu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvzhksa.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpqrsqm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdcueko.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmpmkku.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cowtpdak.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xakevktu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfholbj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsdheud.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tsowbebj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fksifkqa.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2opbwzjol.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgbmbef.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrxgscy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzbtstg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxtaonk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpemxpiq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahrdozh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoaiugs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bntavdkf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbppqslw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2twbdyurb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjedgswu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhisvva.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfoqjlo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2visyytng.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2eatwevsf.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhozydw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvjguzq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvmqhhq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiecdvs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkbzxl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqaagon.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwfaxah.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cbarmdbv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnhmuqt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmrnsez.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdvgoy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkdfegy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjshgevs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbdblry.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdzcgeg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zensphdb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qegogdmc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrxaeku.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vojmozkw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kszcfrjv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtdvvnt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yxybpcqr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afvbebbz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbiynya.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagrrlsh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaxhckx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazwoocp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeblnsmu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2unrkwfom.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuzwcgs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmuvfks.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkrcnah.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wplxsbwb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyrotva.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmjwkev.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuqkdjt.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2toqcxtyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aizshqdf.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgfadil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwrwwah.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwmbhjq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2wganwuiv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zujgpfcz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wysfkdvp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtdsegq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxetswd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcuvtvx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ksciwhwk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvowqbnl.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nswtvnab.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ridmzrrc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgelxez.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iymsahqu.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbophnq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2awfghcry.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgufnat.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvlfgqr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2afhremcl.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wisqmwlr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmnblo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mviuuobm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhsvnub.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyytebfo.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqghyaa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjzfcgz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzflovqd.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2comiqqjx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2clxbotnw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pquwovet.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2drxbgehu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqfqkkd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2muhtwcre.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqwutis.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtofuez.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjozwro.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaybmva.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2chtomcdl.html


<!-- 参考信息 -->